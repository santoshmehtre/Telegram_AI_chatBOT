# Telegram_AI_chatBOT
AI chatbot with open AI and Telegram using program in Python 

## Setting up environvent
- create a new virtual environment by
```python -m venv .venv```
- Install dependencies with requirments file
```pip install -r requirements.txt```
## Creating Telegram Bot
- Open the Telegram app and search for **BotFather** bot.
- Type **/start** to start a conversation with the BotFather.
- Type **/newbot** to create a new bot.
- Follow the instructions provided by the BotFather.
- Once yot created your bot, the BotFather will provide you with an _API token_.
- Go to the Telegram API development tools website [here](https://my.telegram.org/auth)
- Login using your Telegram account.
- Click on **API development tools**.
- Fill out the form to create a **new application**.
- Once you created your app,you will see a page with your **API ID and hash**.
- Make a note of these values as you will need them later to authenticate your bot with Telegram.
## Initialising Pyrogram
- Once you have obtained your API token you need to initialise Pyrogram.
- Here's the file structure for how the project directory should be:
1. bot.py
2. config.py
3. env
4. handlers
    * Message_handler.py
5. requirements.txt
- Create a new file named **bot.py** this will be the main file.
- Create a new file named **Config.py** this file will contain the configuration parameters.
- Create a new directory  named **handlers** this will contain message handler files.
- Inside the handlers directory create a new file named **message_handler.py** this will contain the message handler logic.
- Create a new file named **requirements.txt** this file will contain a list of python packages.
