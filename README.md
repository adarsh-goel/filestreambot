
## USE LATEST CODE FOR BETTER EXPERINCE
### This code also works but I recommend using latest code [Click here](https://github.com/adarsh-goel/filestreambot-pro) to deploy it
### If it doesnt matter keep scrolling 
![GitHub repo size](https://img.shields.io/github/repo-size/adarsh-goel/filestreambot?color=yellow)
[![Telegram Bot](https://img.shields.io/badge/Telegram-Bot-blue.svg)](https://t.me/filetoliprobot)
[![Telegram -Bot](https://img.shields.io/badge/Telegram-Bot_2-purple.svg)](https://t.me/filetoliprorobot)
![GitHub](https://img.shields.io/github/license/adarsh-goel/filestreambot)
[![Bot Support](https://img.shields.io/badge/File%20Stream%20Bot-support%20group-blue)](https://t.me/codexmaniachat)
[![Telegram Channel](https://img.shields.io/badge/Telegram-Channel-blue.svg)](https://t.me/codexmania)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/adarsh-goel/filestreambot)
<h1 align="center">FileStreamBot</h1>
<p align="center">
  <img src="https://socialify.git.ci/adarsh-goel/filestreambot/image?description=1&descriptionEditable=A%20very%20fast%20file%20streaming%20bot%20used%20for%20streaming%20and%20downloading%20movies&font=Source%20Code%20Pro&forks=1&issues=1&language=1&logo=https%3A%2F%2Fuser-images.githubusercontent.com%2F88939380%2F137127129-a86fc939-2931-4c66-b6f6-b57711a9eab7.png&owner=1&pattern=Circuit%20Board&pulls=1&stargazers=1&theme=Dark" alt="Cover Image" width="650">
  

  
  

``` 
💥Superfast⚡️ download and stream links.
💥No ads in generated links.
💥Superfast interface.
💥Along with the links you also get file information like name,size ,etc.
💥Updates channel Support.
💥Mongodb database support for broadcasting.
```
### If you are having issues deploying bot you may sponsor me 5$ through this [link](https://github.com/sponsors/adarsh-goel/) and add your telegram username in issues in this repository with payment proof.

## `Star and fork the repo Before deploying`
   
    
   
   <a href="https://github.com/adarsh-goel/FileStreamBot/issues">Report a Bug</a>
    |
    <a href="https://github.com/adarsh-goel/FileStreamBot/issues">Request Feature</a>
  </p>


<hr>



## 🍁 About This Bot :

![streaming-Professional-live_1](https://user-images.githubusercontent.com/88939380/137127129-a86fc939-2931-4c66-b6f6-b57711a9eab7.png)

</p>

 ### `   This bot will give you stream links for Telegram files without the need of waiting till the download completes`



## ♢ How to make your own :


<b>Deploy on Heroku or Railway:


1. Fork This Repo <br>
2. Click on the button to Deploy and follow steps <br>
  
3.then goto the variables tab for more info on setting up environmental variables. <br>

<h4> So Follow Above Steps 👆 and then deploy other wise bot won't work</h4>

Press the below button to  deploy on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy/)
  
  
 <p><b>Available commands and features:</b>
 
<p>
 
🐬USER COMMANDS<p>
`/start - To start using me` <br>
`/help  -  To know how to use me`

🐬ADMIN COMMANDS<p>
`/status  - to know how many users are using the bot` <br>
`/broadcast - To send message to all the users using the bot`


  
  <b>Host it on VPS Locally :</b></summary>


```py
git clone https://github.com/adarsh-goel/FileStreamBot
cd FileStreamBot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
python3 -m Adarsh
```

and to stop the whole bot,
 do <kbd>CTRL</kbd>+<kbd>C</kbd>

Setting up things

If you're on Heroku just add these in the Environmental Variables
or if you're Locally hosting, create a file named `.env` in the root directory and add all the variables there.
An example of `.env` file:

```py
DATABASE_URL=  Get this from mongodb.com
PORT=8080
API_ID= Get from my.telegram.org
NO_PORT=False
BOT_TOKEN= Get from botfather
OWNER_ID= your owner id 
API_HASH= Get from my.telegram.org
UPDATES_CHANNEL= Enter Force sub channel username without @ if any  else set value to None
BIN_CHANNEL=-100
SESSION_NAME=Codexmania
HAS_SSL=True
FQDN= Enter Custom domain if any or server ip
```
 <b>Vars and Details :</b>
`API_ID` : Goto [my.telegram.org](https://my.telegram.org) to obtain this.

`API_HASH` : Goto [my.telegram.org](https://my.telegram.org) to obtain this.

`BOT_TOKEN` : Get the bot token from [@BotFather](https://telegram.dog/BotFather)

`BIN_CHANNEL` : Create a new channel (private/public), add [@missrose_bot](https://telegram.dog/MissRose_bot) as admin to the channel and type /id. Now copy paste the ID into this field.

`OWNER_ID` : Your Telegram User ID
  
`OWNER_USERNAME` : Your telegram username to be displayed in bot  . make one in you dont have.

`DATABASE_URL` : MongoDB URI for saving User IDs when they first Start the Bot. We will use that for Broadcasting to them. I will try to add more features related with Database. If you need help to get the URI you can ask in [Telegram](https://t.me/codexmania).

 Optional Vars

`UPDATES_CHANNEL` : Put a Public Channel Username, so every user have to Join that channel to use the bot. Must add bot to channel as Admin to work properly.

`BANNED_CHANNELS` : Put IDs of Banned Channels where bot will not work. You can add multiple IDs & separate with <kbd>Space</kbd>.

`SLEEP_THRESHOLD` : Set a sleep threshold for flood wait exceptions happening globally in this telegram bot instance, below which any request that raises a flood wait will be automatically invoked again after sleeping for the required amount of time. Flood wait exceptions requiring higher waiting times will be raised. Defaults to 60 seconds.

`WORKERS` : Number of maximum concurrent workers for handling incoming updates. Defaults to `3`

`PORT` : The port that you want your webapp to be listened to. Defaults to `8080`

`WEB_SERVER_BIND_ADDRESS` : Your server bind adress. Defauls to `0.0.0.0`

`NO_PORT` : If you don't want your port to be displayed. You should point your `PORT` to `80` (http) or `443` (https) for the links to work. Ignore this if you're on Heroku.

`FQDN` :  A Fully Qualified Domain Name if present. Defaults to `WEB_SERVER_BIND_ADDRESS` </details>

<b>How to Use :</b>

:warning: **Before using the  bot, don't forget to add the bot to the `BIN_CHANNEL` as an Admin**
 
`/start` : To check if the bot is alive or not.



To get an instant stream link, just forward any media to the bot and boom, its fast af.
  ![image](https://user-images.githubusercontent.com/88939380/137128326-059f9c53-b3d0-40f0-8484-b17709fbcc11.png)


### Channel Support
`Bot also Supports with Channels. Just add bot Channel as Admin. If any new file comes in Channel it will edit it with Get Download Link Button.` </details>

### 🔷 Credits : 

- [Adarsh Goel_(me)](https://t.me/codexmania)
- Everyone In This Journey !
- `Feel free to contribute 😀`

  
 
 
