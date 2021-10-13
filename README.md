# Telegram Music Bot
Telegram Music Bot for YouTube/SoundCloud/Mixcloud

This bot downloads and sends the audio when someone send a YouTube/SoundCloud/MixCloud link
in the specified chats, there is a command `/ping` which makes the bot reply with a "ping"
for checking if the bot is running.

## How to deploy 

Click the below button to watch the video tutorial on deploying

<a href="https://youtu.be/fneLD-2NgWg"><img src="https://img.shields.io/badge/How%20To%20Deploy-blue.svg?logo=Youtube"></a>
<a href="https://youtu.be/fneLD-2NgWg"><img src="https://img.shields.io/youtube/views/fneLD-2NgWg?style=social">


## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/lushaimusic/tgmusicbot)

## Manually

```# Telegram API Key
# get from https://my.telegram.org/apps
export API_ID="123456789"
export API_HASH="0123456789abcdef0123456789abcdef"

# Telegram Bot Token
# get from https://t.me/BotFather
export BOT_TOKEN="123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11"

# One or more user/group username/id the bot serve to,
# separate with space
export MUSIC_CHATS="-1001210609718 username"

# install ffmpeg
apt install ffmpeg

virtualenv venv
venv/bin/pip install -U -r requirements.txt
venv/bin/python bot.py```

## License

AGPL-3.0-or-later
