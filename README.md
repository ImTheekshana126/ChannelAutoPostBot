# Channel Auto-Post Bot

This bot can send all new messages from one channel, directly to another channel (or group, just in case), without the forwarded tag!

## Setting up 
* First:
> `APP_ID` and `API_HASH` - Get it from my.telegram.org   
> `BOT_TOKEN` - Get it from [@BotFather](https://t.me/BotFather)   
> `FROM_CHANNEL` - The ID of the main channel from where posts have to be copied. (Use @chnlidbot to get it.)   
> `TO_CHANNEL` - The ID of the channel to which the posts are to be sent. (Use @chnlidbot to get it.)   
   
* Chose a platform to deploy on:
<details>
<summary>Heroku/Kintohub/Zeet</summary>
<br>
Add the above values to the environment vars and deploy the bot.
</details>
<details>
<summary>Local Deploys</summary>
<br>
- Clone the repo:   <code>git clone https://github.com/imtheekshana126/ChannelAutoForwarder</code></br>
- Make a <code>.env</code> file in the root of the repo, like <a href="https://github.com/imtheekshana/ChannelAutoPostBot/blob/main/.env.sample">.env.sample</a> and fill in the values.</br>
- Use <code>python3 bot.py</code> to start the bot.</br>  
</details>

## Usage
Add the bot to both channels with admin permission, and thats it!
All new messages will be auto-posted!!

Visit [THEEKSHANA OFFICIAL](https://t.me/theekshana_Official) for help.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

