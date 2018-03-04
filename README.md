# Carbot

This is a bot built in Python 3 to use with Slack. It will store and update who has what car. New cars and names are able to be added or removed.

You will need to have a Slack account and create a Slack App to receive an API token for the bot. The Bot User OAuth Access Token should be stored as an environmental variable. So in your terminal while in your project folder, you would type the following:

`export SLACK_BOT_TOKEN='your bot user access token here'`

You will also need to create 2 files: `names.txt` and `inventory.txt`. These files store the users' names and who has what car.

In order to use your bot, you will need to invite it to the Slack channel where you want to use it.