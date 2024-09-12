Simple Telegram Bot
===================

This repository contains a basic Telegram bot built using Python and the python-telegram-bot library. The bot provides users with a set of interactive buttons and responds to commands such as /start and /help. It's a simple template for building more advanced bots with command handling, inline keyboard interactions, and custom features.

Features
--------

*   Responds to the /start command with a welcome message and displays interactive buttons.
    
*   Users can select from options using inline buttons.
    
*   Responds to the /help command with a list of available commands.
    
*   Handles button selections and dynamically updates the message based on the user’s choice.
    

Requirements
------------

Before running the bot, make sure you have the following:

1.  Python 3.6 or later
    
2.  bashCopia codicepip install python-telegram-bot --upgrade
    

Getting Started
---------------

### 1\. Clone the Repository

`git clone https://github.com/your-username/simple-telegram-bot.git`

### 2\. Get Your Bot API Token

You need to create a new bot on Telegram and get an API token from BotFather. Follow these steps:

1.  Start a chat with BotFather.
    
2.  Use the /newbot command to create a new bot.
    
3.  Copy the API token provided by BotFather.
    

### 3\. Add Your API Token

Replace 'YOUR\_API\_TOKEN' in the code with your actual Telegram bot token:

`   API_TOKEN = 'YOUR_API_TOKEN'   `

### 4\. Run the Bot

Once you’ve set your bot token, you can run the bot with:

`   python telegram_bot.py   `

The bot will start polling for updates and will respond to /start and /help commands, as well as handle button selections.

Bot Commands
------------

*   **/start**: Starts the bot and displays a welcome message along with option buttons.
    
*   **/help**: Displays a list of available commands.
    

Code Explanation
----------------

*   start: This function handles the /start command and displays a welcome message along with inline keyboard buttons.
    
*   show\_option\_buttons: Displays three buttons for the user to interact with.
    
*   button\_selection\_handler: Handles the button selections and updates the message based on the user's choice.
    
*   help\_command: Provides the list of available commands to the user.
    
*   main: The main function that sets up the bot and starts polling for messages.
    

Example Interaction
-------------------

1.  User sends /start.
    
2.  The bot replies with a welcome message and three option buttons.
    
3.  User clicks on one of the buttons.
    
4.  The bot replies with the selected option.
    

License
-------

This project is open-source and available under the MIT License.
