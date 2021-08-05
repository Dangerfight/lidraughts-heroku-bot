# MAINTAINER [UnknownStrongPlayer](https://lidraughts.org/@/UnknownStrongPlayer)


# lidraughts-bot

- A bridge between [Lidraughts API](https://lidraughts.org/api#tag/Bot) and bots.
- This bot is using Docker and concentrated on Heroku server.

## How to Install In Heroku

- Import or Fork this repository to your Github.
- Open config.yml and insert API accses token in to token option and commit changes
- Install [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) and create app in Heroku.com.
- Run this in cmd `heroku stack:set container -a appname` replace appname with your Heroku app's name.
- Connect app with Github and deploy app in Heroku.
- After deploying turn worker on in Resources menu in Heroku. 

## INFO 

ENGINE:
- SCAN


**If you want to run bot localy on PC, read the [lidraughts-bot manual](https://github.com/AttackingOrDefending/lidraughts-bot).**

### Acknowledgements
Credits to [AttackingOrDefending](https://github.com/AttackingOrDefending/lidraughts-bot)'s lidraughts-bot 
