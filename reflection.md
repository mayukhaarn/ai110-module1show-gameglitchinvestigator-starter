# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").

  1. Hints were incorrect for the guess. The hint would tell the user to "Go Lower" when it should have stated for them to go higher and tell the user to "Go Higher" when it should have suggested for the user to go lower. 
  2. The game states that 8 attempts are allowed, but the game only stops the user once 11 attempts are reached. 
  3. The "New Game" button doesn't work and reset the array.

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
Copilot
Prompt: Search this codebase for the vital error where the system displays "Go Lower" when the guess is lower than the secret key and displays "Go Higher" when the guess is greater than the secret key. Do not make any edits without permission and first identify where the issue is before providing some examples of possible changes that can be made to fix this error.

- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
Suggested refactoring code to improve logic.
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
AI suggestion wanted to revise only part of the hints being reversed, I had to guide it to implement this edit both ways.


---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
