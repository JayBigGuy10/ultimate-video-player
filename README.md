# ultimate-video-player

## Read my project report document [here!](https://github.com/JayBigGuy10/ultimate-video-player/blob/main/Jayden%20Litolff%20-%20COMPX241%20Individual%20Report%20%26%20Logbook%20-%20UltimateVideoPlayer.pdf)


## Team Members

Project Manager: 
- Michael Peddie

Team Members: 
- Luke Fraser-Brown
- Jayden Litolff
- Shreyaa Senthil Kumar
- Jack Unsworth
- Leo Van Der Merwe

## How to run this weird stack
<code>cd web-app & npm install & npm run dev</code>

In another terminal
<code>cd backend/BackendEnv</code>
<code>run install.ps1 (this makes a python venv, pip installs from requirements.txt and adds ffmpeg to the current shells PATH)</code>
<code>cd backend && flask run</code>


## Note for Jayden, how to expose the stack
- tailscale funnel -https 10000 127.0.0.1:8000
- tailscale funnel 127.0.0.1:5173

## How to get the pip venv list
pip freeze > requirements.txt

## Whisper not importing?
pip install -U openai-whisper
