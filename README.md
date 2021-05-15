# Telegram-VC-SingerBot

## Requirements

- Telegram API_ID and API_HASH
- Python 3.7 or higher 
- Userbot Needs To Be Admin In The Chat
- Install **ffmpeg**

## Run

```sh
$ git clone https://github.com/mastermindvrtx/Telegram-VC-SingerBot
$ cd Telegram-VC-SingerBot
$ sudo apt-get install ffmpeg
$ pip3 install -U pip
$ pip3 install -U -r requirements.txt
$ cp sample_config.py config.py
```
Edit **config.py** with your own values.

```sh
$ python3 main.py
```

## Heroku

#### Generate String session [IMPORTANT]

Download this file [generate_string_session.py](https://raw.githubusercontent.com/mastermindvrtx/Telegram-VC-SingerBot/dev/generate_string_session.py)


```sh
$ pip3 install pyrogram TgCrypto
$ python3 generate_string_session.py
```
Fork this repository and change name of `sample_config.py` to `config.py`
Then you will need get a session string, copy it, then press heroku deploy button.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/mastermindvrtx/Telegram-VC-SingerBot/tree/dev)


