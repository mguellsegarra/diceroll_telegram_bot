# Diceroll Telegram Bot

An easy implementation of a Telegram bot for rolling the dice. Thanks to [@yagop](https://github.com/yagop) for his fantastic [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) library. Also thanks to [@takkytsubasa](telegram.me/takkytsubasa) for showing interest in my work and encourage me to publish it.

There are two bots running this software and available for everyone in Telegram:

- *[@DiceRollBot](telegram.me/RollDiceBot)* - English bot for rolling the dice
- *[@TiraDausBot](telegram.me/TiraDausBot)* - Same bot for catalan speakers

## Usage

Just clone this repo and edit `config.json` file in order to change the bot API key.

Run it!

```
# node index.js
```

And enjoy rolling the dice.

I personally use [pm2](https://github.com/Unitech/pm2) to run it in my server.

## i18n

The bot supports i18n, so you can specify a locale:

```
# node index.js --locale ca
```

The localization files are found in `locales/` folder. Default locale if you don't specify any is english `en`.

Feel free to open PR's if you want to contribute adding more languages!

## License 

The MIT License (MIT)

Copyright (c) 2017 Marc Güell Segarra

