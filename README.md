# Working Rocket.Chat Python Bot
Rocket.Chat Python basic bot using dpp
Forked from https://github.com/maxux/python-rocketchat-bot

# Dependencies
`emerge -va python-meteor`
or
`pip install python-meteor`

# Usage
```
def hello(bot, message):
    bot.sendMessage(message['rid'], "React from hello command")

rocket = RocketChatBot('username', 'password')
rocket.addPrefixHandler('hello', hello)
rocket.start()
```
