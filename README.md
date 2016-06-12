# telegram-bot-webhook
A simple telegram bot server in node.js using webhook.

see: [Configure a telegram bot webhook into an existing express app](http://mvalipour.github.io/node.js/2015/12/06/telegram-bot-webhook-existing-express/)

# Getting Started
To test in a local environment you need to create a `.env` file in the root directory of the project and run heroku local

To run online you need to set a couple of config vars with `heroku config:set TOKEN=youmustputherethebottoken` and `heroku config:set HEROKU_URL=$(heroku info -s | grep web-url | cut -d= -f2)`
