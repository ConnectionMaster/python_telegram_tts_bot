# python_telegram_tts_bot
> Telegram bot that does TTS & STT via Yandex SpeechKit on python

[![Build Status](https://travis-ci.org/KaltakhchyanD/python_telegram_tts_bot.svg?branch=master)](https://travis-ci.org/KaltakhchyanD/python_telegram_tts_bot)
[![Maintainability](https://api.codeclimate.com/v1/badges/6f19a9b8c1e0080f66b9/maintainability)](https://codeclimate.com/github/KaltakhchyanD/python_telegram_tts_bot/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/6f19a9b8c1e0080f66b9/test_coverage)](https://codeclimate.com/github/KaltakhchyanD/python_telegram_tts_bot/test_coverage)

With this bot written on python3 with python-telegram-bot (<https://github.com/python-telegram-bot/python-telegram-bot>), you can create a bot that converts text message from a user into an audio file and voice message into text.

Take into consideration that it's my pet project.


## Before installation
You have to register your bot at BotFather and create Yandex Cloud account. More on that down below
Also you need to obtain 4 tokens:
 - telegram bot api token (<https://core.telegram.org/bots#6-botfather>)
 - IAM token (<https://cloud.yandex.com/docs/speechkit/concepts/auth>)
 - Folder_ID - id your folder at Yandex Cloud. More on Yandex Cloud (<https://cloud.yandex.com>)
 - Get an OAuth token from Yandex.OAuth. To do this, follow the link (<https://oauth.yandex.com/authorize?response_type=token&client_id=1a6990aa636648e9b2ef855fa7bec2fb>), click Allow and copy the OAuth token that is issued.

This bot uses this tokens as env variables - you should export them locally by yourself with these exact names:

```sh
 export API_KEY_BOT=...
 export IAM_TOKEN=...
 export FOLDER_ID=...
 export OauthToken=...
```

## Installation

OS X & Linux:

git clone 

python3 -m venv env

./env/bin/activate

pip install -r requirements.txt

ENV VARS!

python bot.py


 pip install -r

## Usage example

A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.

## Contributing

1. Fork it (<https://github.com/KaltakhchyanD/python_telegram_tts_bot/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[python-telegam-bot]: https://github.com/python-telegram-bot/python-telegram-bot
