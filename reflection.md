# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

The game had a bad memory and picked a new secret number everytime I clicked a button. The hints were also backwards, telling me to go higher when I was already too high. Many of the game's math rules were unfinished or messy, which caused the game to crash or act weird. 

## 2. How did you use AI as a teammate?

I used the AI to guide me explain how to give the game a memory and to help fix the broken hints. It was helpful when it showed me how to save the secret number, but sometimes it suggested code that didn;t match the rest of the game. I treated the AI like a helper, I listened to the ideas but always tested them myself to make sure they actually wworked. 

## 3. Debugging and testing your fixes

I knew a bug was fixed when the pytest tool gave me a green pass and the game felt right when I played it. I used the developer debug info to cheat and see the secret number, which helped me confirm the hints were finally accurate. The AI helped me write the fixes but overall I was the one who ran the tests to prove they were correct.
## 4. What did you learn about Streamlit and state?

I learned that Streamlit restarts the whole script everytime you click anything. Because of this, I noticed normal variables get erased instantly. I learned to use st.session_state as a digital notebook to save important info like the secret number and score so the game doesn't forget them.

## 5. Looking ahead: your developer habits

In the future, I will keep my brain code separate from my display code so it's easier to fix. This project taught me that while AI is fast builder, I need to be the supervisor who double checks everything with tests. I won't just copy and paste, I'll test small pieces as I go. 