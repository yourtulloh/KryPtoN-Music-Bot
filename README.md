# KryPtoN Music Bot

[![Actions Badge](https://img.shields.io/github/workflow/status/Kry9toN/KryPtoN-Music-Bot/PyCheck/master?label=Build&style=flat-square&logo=github-actions&logoColor=white&color=98CE00)](https://github.com/Kry9toN/KryPtoN-Music-Bot/actions)
[![Codacy Badge](https://img.shields.io/codacy/grade/6275e97d871b45458235492edfa77745?style=flat-square&logo=codacy&color=17BEBB)](https://www.codacy.com/gh/Kry9toN/KryPtoN-Music-Bot/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Kry9toN/KryPtoN-Music-Bot&amp;utm_campaign=Badge_Grade)

![Watch Badge](https://img.shields.io/github/watchers/Kry9toN/KryPtoN-Music-Bot?label=Watch&style=flat-square&logo=github&color=FF70A6goColor=white&color=98CE00)
![Start Badge](https://img.shields.io/github/stars/Kry9toN/KryPtoN-Music-Bot?label=Stars&style=flat-square&logo=github&color=F8757598CE00)
![Fork Badge](https://img.shields.io/github/forks/Kry9toN/KryPtoN-Music-Bot?label=Fork&style=flat-square&logo=github&color=E0777D)

Music on Voice Calls Telegram

[![Image Preview](https://raw.githubusercontent.com/Kry9toN/KryPtoN-Music-Bot/master/etc/preview.jpg)](https://github.com/Kry9toN/KryPtoN-Music-Bot)

# Support
- Python 3.7 or above
- All distro linux (Ubuntu 18.04 not work)
- Windows
- Mac

# Requirements
- Telegram API_ID and API_HASH [Get here](https://my.telegram.org/apps)
- Python 3.7 or higher
- Needs user account not bot from bot father
- Install ffmpeg

# Usage
Install package required
```
$ git clone https://github.com/Kry9toN/KryPtoN-Music-Bot
$ cd KryPtoN-Music-Bot
$ pip install -r requirements.txt
```
Setup config
configs.py and edit

Execute!
```
$ python3 -m krypton
```

# Heroku 

[![Heroku Badge](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Kry9toN/KryPtoN-Music-Bot/tree/master)

### Generate String session [IMPORTANT]
Download this file [generate_string_session.py](https://raw.githubusercontent.com/Kry9toN/KryPtoN-Music-Bot/master/generate_string_session.py)

```
$ pip3 install pyrogram TgCrypto
$ python3 generate_string_session.py
```
You will get a session string, copy it, Then use heroku commands to push to heroku

## Commands
Command | Description
:--- | :---
/start | To Start The bot.
/help | To Show This Message.
/ping | To Show Latency Bot.
/skip | To Skip The Current Playing Music.
/play | youtube/saavn/deezer song_name
/stop | To Stop Playing Music.
/join | To Join A Voice Chat.
/leave | To Leave A Voice Chat.
/mute | To Mute A Bot.
/unmute | To Unmute A Bot.
/volume | <1-200>
/kill | To Kill A Sevice Bot.
/donation | To Give Me A Coffe.

## To-Do
- add moar feature

# Donation
- [Saweria](https://saweria.co/donate/Kry9toN)
- [Paypal](https://www.paypal.me/KomodoOS)

# License
[GPL-3.0 License](https://github.com/Kry9toN/KryPtoN-Music-Bot/blob/master/LICENSE.md) KryPtoN © 2021

# Credit
- [@MarshalX](https://github.com/MarshalX)
- [@thehamkercat](https://github.com/thehamkercat)
