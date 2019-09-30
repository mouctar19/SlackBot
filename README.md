<div align="center">
    
# TechQuote SlackBot

![inspireNuggets](https://github.com/BolajiAyodeji/inspireNuggets/raw/master/tab-icon.png)

A simple Slackbot that displays random inspiring techie quotes and jokes for developers/designers :zap:

# Setup

### Clone the repository

```
git clone https://github.com/BolajiAyodeji/inspireNuggetsSlackBot.git && cd inspireNuggetsSlackBot
```

### Install dependencies

```
npm install

npm start
```

### [Create a bot in Slack](https://api.slack.com/apps/AM92STGGG/general?) and generate and include your OAuth bot token

```
// Add this in your .env
BOT_TOKEN=YOUR_OWN_BOT_TOKEN
```

```js
const bot = new SlackBot({
    token: `${process.env.BOT_TOKEN}`,
    name: 'YOUR_OWN_APP_NAME'
})
```
