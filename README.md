<h2 align="centre">VIDEO STREAM BOT</h2>

## 🛠 Commands:
- /vplay (reply to video/give yt url) - to start video streaming
- /vstop - to stop video streaming
- /song (song name) - to download song
- /vsong (video name) - to download video
- /vjoin - invite the assistant join to your group
- /vleave - order the assistant to leave from your group
- /lyric (query) - lyric scrapper
- /tts (reply to text) - text to speech
- /alive - check the bot alive status
- /ping - check the bot ping status
- /uptime - check the bot uptime status
- /sysinfo - show the bot system information

## 🧙🏻‍♂️ Sudo Only:
- /rmd - clear all downloaded files
- /rmw - clear all downloaded raw files
- /leaveall - order the assistant to leave from all group

📝 Note: From now, /vstream & /vstop command can only be used by group admins.

## 🧪 Get STRING_SESSION from below:

TAP THIS: [![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@levinalab/StringSession#main.py)

## Heroku Deployment 💜
The easy way to host this bot, deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/qowwim-lab/vstream)

# Railway Deployment 🚄
[![Deploy+on+Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/qowwim-lab/vstream&envs=API_ID,API_HASH,BOT_TOKEN,BOT_USERNAME,ASSISTANT_NAME,SESSION_NAME,SUDO_USERS,DURATION_LIMIT)

## VPS Deployment
```sh
- sudo apt update && upgrade -y
- sudo apt install python3-pip -y virtualenv
- sudo apt install ffmpeg -y
- nvm install v16.5.0
- npm i -g npm
- git clone https://github.com/qowwim-lab/vstream
- cd video-stream
- virtualenv venv #Create Virtual Environment.
- source venv/bin/activate #Activate Virtual Environment
- pip3 install --upgrade pip
- pip3 install -U -r requirements.txt
- cp -r sample.env local.env
- nano local.env #Fill it with your variables value.
- python3 -m bot
```

# Special Credits 💖

- [Levina](https://github.com/levina-lab) Dev
- [Sammy-XD](https://github.com/Sammy-XD) Dev
- [MarshalX](https://github.com/MarshalX) for [pytgcalls](https://github.com/MarshalX)
- [Dan](https://github.com/delivrance) for [Pyrogram](https://github.com/pyrogram)

