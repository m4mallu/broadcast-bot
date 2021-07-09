# [Broadcast Bot](https://t.me/RMProjects)

A Telegram bot to send messages and medias to the subscribers directly through bot.

 - Authorized users of the bot can send messages (Texts or Media) within the bot.
 - Those who have started the bot, will receive the above posts.
 - Authorized users can get the subscriber count also.

<br>

## Deploy to Heroku:
<p align="left">
  <a href="https://heroku.com/deploy?template=https://github.com/m4mallu/broadcast-bot">
     <img height="30px" src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku">
  </a>
</p>

## Variables:

* `API_HASH`    Your API Hash from my.telegram.org
* `API_ID`      Your API ID from my.telegram.org
* `BOT_TOKEN`   Your bot token from @BotFather
* `AUTH_USERS`  Create a list of User Ids to use this bot
* `DB_URI` Create a postgre database if you deploy the locally | In heroku do nothing  
* `SUPPORT_CHAT` Public group / channel username of the support chat

## @BotFather Commands
```
send - send posts to the subscribers (Admin Only)
subscribers - view subscribers count (Admin Only)
```

## Deploy Locally:

Create a `config.py` with the above variables (Refer sample_config.py)
```
git clone https://github.com/m4mallu/broadcast-bot
cd broadcast-bot
virtualenv -p python3 venv
. ./venv/bin/activate
pip3 install -r requirements.txt
python3 bot.py
```
<br>


#### [Join Telegram Bot Update Channel](https://t.me/RMProjects)

For deploy locally : [How to create a database URI](https://telegra.ph/inline-directory-bot-help-06-19) | Refer
Clonebot's help, to create a database.

## Developer: [𝑅𝑒𝓃𝒿𝒾𝓉𝒽 𝑀𝒶𝓃𝑔𝒶𝓁](https://t.me/space4renjith)

<p align="center">
    <a href="https://t.me/space4renjith">
        <img alt="GPL3" src ="https://telegra.ph/file/c4f778ccfc576a954dd20.gif" width="340" height="214"/>
    </a>
</p>
