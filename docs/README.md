<h1 align="center">
  SActive Bot
</h1>

<h4 align="center">
  :smiling_imp: An extensible chat bot framework.
</h4>

<p align="center">
  <a href="https://www.travis-ci.org/shipengqi/sactive-bot">
    <img alt="Build Status" src="https://img.shields.io/travis/shipengqi/sactive-bot/master.svg?style=flat-square">
  </a>
  <a href="https://www.npmjs.com/package/sactive-bot">
    <img alt="NPM version" src="https://img.shields.io/npm/v/sactive-bot.svg?style=flat-square">
  </a>
  <a href="https://www.npmjs.com/package/sactive-bot">
    <img alt="NPM Download" src="https://img.shields.io/npm/dw/sactive-bot.svg?style=flat-square">
  </a>
  <a href="https://github.com/shipengqi/sactive-bot/blob/master/LICENSE">
    <img alt="License" src="http://img.shields.io/npm/l/sactive-bot.svg?style=flat-square">
  </a>
</p>

<p align="center">
 Create a Mattermost bot:
</p>
<div align="center">
  <img alt="Create a Mattermost bot" src="img/sbot_demo.gif" width="65%">
</div>

<p align="center">
 Chat with bot:
</p>
<div align="center">
  <img alt="Chat with bot" src="img/chat_bot_demo.gif" width="65%">
</div>


## Requirements
- `NodeJs` version `v7.9+`

## Installation
### Clone source code form GitHub
```bash
# clone
git clone git@github.com:shipengqi/sactive-bot.git

# install dependencies
cd sactive-bot
yarn install

# link
npm link
```

### NPM ot Yarn
```bash
npm install sactive-bot -g

# or
yarn global add sactive-bot
```

## Features
- WeChat Bot
- Slack Bot
- Mattermost Bot
- Microsoft Teams Bot
- Support create conversation for bot
- Misspelling
- Help for bot
- Conversation Manager
- Command API call
- Support integrate your own adatper

## Documentations
- [Getting Started](getting_started.md)
- [Create a WeChat Bot](wechat_bot.md)
- [Create a Slack Bot](slack_bot.md)
- [Create a Mattermost Bot](mattermost_bot.md)
- [Create a Microsoft Teams bot Bot](msteams_bot.md)
- [Writing your scripts](scripts.md)
- [Command receiver](command_receiver.md)
- [Conversation Guide](conversation_guide.md)
- [External Adatper](external_adapter.md)

## TODO
- Unit Test
- Command authentication
- Bot server authentication
- Crypto all sensitive information
- Render card
- Docker version, kubernetes yaml file
- Wechat Adapter
  - [WeChat Protocol](http://www.blogjava.net/yongboy/archive/2015/11/05/410636.html)
  - [WeixinBot](https://github.com/Urinx/WeixinBot)
  - [WeChat communication process](http://www.tanhao.me/talk/1466.html/)
- Mattermost Adapter
  - [hubot-matteruser](https://www.npmjs.com/package/hubot-matteruser)
  - [API doc](https://api.mattermost.com/)
- Slack Adapter
  - [hubot-slack](https://github.com/slackapi/hubot-slack)
- Microsoft teams Adapter
  - [TeamsAPI](https://github.com/howdyai/botkit/blob/master/lib/TeamsAPI.js)