# SUMS MD 1400 Telegram Bot v 1.0
[![LICENSE](https://img.shields.io/badge/LICENSE-GPL--3.0-green)](https://github.com/AlirezaChinian/SUMS-1400-Telegram-Bot/blob/main/LICENSE)
[![Supported Python versions](https://img.shields.io/pypi/pyversions/python-telegram-bot.svg)](https://www.python.org)
[![Bot API versions](https://img.shields.io/badge/Bot%20API-5.7-blue?logo=telegram)](https://api.telegram.org)

Official Telegram Bot of SUMS MD 1400 with full admin panel in Bot and also with flask app and a Support Bot.
## Requirements
* Python3
* pip
* [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
* [flask](https://github.com/pallets/flask)
* flask-login
* flask-limiter
* [requests](https://github.com/psf/requests)
## How to run it?
1. Install Requirements: 
```
  $ pip3 install -r requirements.txt
```
2. Run database.py to create database and tables and also insert test user information:
```
  $ python3 database.py
```
3. Define Main Bot and Support Bot Token in config.py
4. Define Bot admins(needs admins user_ids) in config.py
5. Define Channel_id(needs for mandatory membership) in config.py
6. Define Site Address in config.py
7. Define Sec token and Secret key in config.py
8. Deploy flaskapp on server with apache2 or nginx
9. Run bot.py to start Main Bot: 
```
  $ python3 bot.py
```
10. Run talkbot.py to start Support Bot:
```
  $ python3 talkbot.py
```

> Note: File IDs are unique for each Bot Token so sending file won't work and you will get error(Telegram rules! :) ).
## Credits
[SUMS MD 1400 Bot](https://t.me/sums1400_bot)

[SUMS MD 1400 Website](https://sumsmd1400.ir)
## License
SUMS MD 1400 Telegram Bot is licensed under the [GNU General Public License v3.0](https://github.com/AlirezaChinian/SUMS-1400-Telegram-Bot/blob/main/LICENSE)
