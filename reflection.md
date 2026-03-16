# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

- It appeared to work and look functionable but I was able to notice some issues. The hint direction seemed to be backwards, since my guess was lower than the answer. The score was also showing a negative number and I wasn't sure what it was supposed to reflect. Finally, the "new game" button doesnt work.
---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

- Copilit with Claude
- The messages being swwapped for the hints
- It says log_utils.py is empty, when it's not 
---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

- I would check the website again 
- I was looking at the test and it showed there was stil a lot wrong with my code, so I had to keep working with the other eroes
- Yes! It highlighted issues I was confused with and told me why they were wrong.

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

Everytime I type something into the streamlit, the entire files reruns from the top. Which means all varaibles get reseted to it's starting value. When we our doing our code, teh number wasn't being saved properly so it got reset to a starting variable, which was another randomized number between the range. 
---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?

- When I tell copilit how the code is supposed to work, and it asking me any questions regarding what I explained, just to get it more familiarized with what the website is supposed to do. 

  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?

- I initially asked what was wrong with the code, which was incredibly broad and hard to pinpoint without my assistane. 

- In one or two sentences, describe how this project changed the way you think about AI generated code.

- AI generated code depends on your understanding of the code, and how it will work with your understanding and what it is recieved.
