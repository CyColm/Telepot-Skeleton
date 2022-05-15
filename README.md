# Telepot-Skeleton

Skeleton for a Telegram bot

## Prerequisites

You need to create a bot with [botfather](https://t.me/botfather) [help](https://core.telegram.org/bots).

To continue, you will need a token and your Telegram chat_id to create tokens.py according to tokens.py_example

## Installation

A [git](https://git-scm.com/) clone is required to install Telepot-Skeleton.

```bash
git clone https://github.com/CyColm/Telepot-Skeleton.git
```

## How it's made

This skeleton contains :

- bot.py :                it's the entry point
- botConfig.py :          manager of settings.ini
- botData.py :            (optional) database manager if needed
- botTools.py :           a tool box where you can write all of your functionality
- mainMessageHandler.py : as the name suggests it's the message handler, based on menu.json
- menu.json :             this is your menu description
- routine.py :            code in the method "action" will be running regularly according to the
                        time defined in poll settings
- tokens.py :             it's your sensitive information according to the template provided

bot.py is a basic script that instantiates all objects and starts a chat by sending a keyboard.
A routine is created and send a message each 7 hours by default.


## Usage

You need to create a "tokens.py" file that contains the previously telegram bot token made by botFather and your chat_id. You can find it by sending "/start" to userinfobot on Telegram.

Next step, you have to custom your menu and add features in botTools according to examples.

Then start using it !


> ###### N.B:
> 
> "settings.ini" file is created on start.
> 
> This skeleton use advanced [telepot](https://telepot.readthedocs.io/en/latest/) package.
> It uses asynchronous for chat and multithreading for the routine.
> All bots I found on Github are simply in traditional version of telepot.


## Screenshots

---------- On start -------------------------------------------- Test of each menu ------------------------------- Back button ----------


![chat1](/docs/chat1.jpg)
![chat2](/docs/chat2.jpg)
![chat3](/docs/chat3.jpg)
![chat4](/docs/chat4.jpg)


## Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss what you would like to change.

Feel free to fork it !
