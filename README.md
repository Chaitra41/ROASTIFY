# ROASTIFY

**Roastify Me**
Roastify Me is a fun, interactive web app that playfully roasts or compliments users based on their mood and input. Whether you're feeling down or too proud of yourself, this app's got just the right amount of sass or sweetness for your day.
**Features**
🔥 Roast or 💖 Compliment — Choose your vibe

🪞 Mirror Mode — Turns your words against you (playfully)

🎙️ TTS Playback — Hear your roast/compliment read out loud

🎲 Random Surprise — Let fate decide your sass

📜 Roast/Compliment History — Track your past burns and boosts

🎞️ Fun Giphy Reactions — Get visual reactions for each message
**Tech Stack**
Technology	Purpose
Streamlit	Frontend & UI
TextBlob	Mood/Sentiment Analysis
gTTS (Google Text-to-Speech)	Voice playback of roasts/compliments
Giphy	GIF Reactions
roast_engine.py, compliment_engine.py	Custom NLP logic for roasts & compliments
**How it Works**
Users input a phrase or sentence.
Sentiment is analyzed using TextBlob or overridden by a slider.
Depending on the selected mode, the app returns either:
a roast (snarky remark), or
a compliment (kind & uplifting message)
Result is read aloud using gTTS and paired with a random Giphy reaction.
All responses are logged to roast_log.txt.
**Run the app**
streamlit run app.py
**Requirements**
Your requirements.txt might look something like this:
streamlit
gtts
textblob
**Mirror Mode**
Turn your own words against you. Roastify will twist what you said into a roast — no filters, just drama. 😏






