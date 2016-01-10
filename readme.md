# About
This is a simple bot that sits in a slack channel and will look up card information for either Android: Netrunner and A Game of Thrones (depending on configuration).

# Setup
To use this bot you will need a nodejs server and git to clone this repo.

1. From this project's directory type: npm install
2. Add a slack bot to your server.
3. Edit the config.json so that CARD_DB_URL is set to http://netrunnerdb.com or http://thronesdb.com.
4. Edit the config.json so that SLACK_BOT_TOKEN is set to your slack bot's API key.
5. From this project's directory type: node app.js

# Usage
Simply type the name of a card surrounded by square brackets anywhere in your message and the bot will attempt to look it up (ie \[ttidfl\]. Acronyms and partial matches work! 

# Todo

# License
Copyright (c) 2016 Eamon White Licensed under the MIT license.