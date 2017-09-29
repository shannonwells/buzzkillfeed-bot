# !["Buzz Killfeed Logo"](https://github.com/shannonwells/buzzkillfeed/blob/master/assets/buzzkillfeed-icon-sm.png ) Buzz Killfeed

A Slackbot for Clickbait Generator written for Node.js.  It uses the node-slack-client library.

"Buzz Killfeed to the Rescue!"

## How To Do It

1. On Slack.com, create a bot for your team, and save the resulting API token
1. Invite your bot to your channel.
1. On your server/laptop/herokuapp, Install node
1. Clone this repo
1. Set BUZZKILLFEED_SLACKBOT_TOKEN to the above API token.
1. Set CLICKBAIT_GENERATOR_URL - which might be mine, or it might be your own Clickbait Generator hack/fork/blatant-ripoff.
1. Set CHANNEL_NAMES - a list of channel names on which we should try to listen (separated by spaces)
1. ```npm install```
1. ```node bin/www```
1. To debug, change 'warn' to 'debug'
1. Talk to or about your bot

Note: it appears that as the bot gets invited to channels, it will listen
so CHANNEL_NAMES should be optional.
