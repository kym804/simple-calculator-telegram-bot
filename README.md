# python-telegram-bot
Telegram bot compatible with Python 3.7. Webhooks with ngrok to Telegram bot message stream, conditional responses.

## Instructions For Use:
Download ngrok into the project root directory: https://ngrok.com/download

Navigate the the root directory in terminal, run:

> ngrok http 5000

Add your telegram bot token to the TOKEN variable in config.py

Add your ngrok forwarding https url to the NGROK_URL variable in config.py

Install Flask Framework using pip:

> pip install -U Flask

Configure conditional actions based on Telegram message text in telegram_bot.py TelegramBot.action class method

Run the app server however you have python3.7 set to PATH:
> python3.7 app.py
