**<h1 align="center">ππΆ π΅πΈπ»π΄ ππΎ π»πΈπ½πΊ π±πΎπ</h1>**
<p align="center">
  <a href="https://youtu.be/W4wSOZw8GXk">
    <img src="https://telegra.ph/file/a2303826e0c6d18bf9cab.jpg">
  </a>
  <p align="center">
    πΈ π²π°π½ πΆπ΄π½π΄ππ°ππ΄ π³πΈππ΄π²π π³πΎππ½π»πΎπ°π³ π»πΈπ½πΊ π΅πΎπ π°π½π ππΈπ³π΄πΎ/π΅πΈπ»π΄π π΅πΎπ π³πΎππ½π»πΎπ°π³πΈπ½πΆ πΎπ½π»πΈπ½π΄ & π΅πΎπ ππππ΄π°πΌπΈπ½πΆ...
    <br />
    <a href="https://telegram.dog/OP_FileToLinkBot"><strong>π΅πΈπ»π΄ ππΎ π»πΈπ½πΊ π±πΎπ Β»</strong></a>
    <br />
  </p>
  <p align="center">
  <a href="https://youtube.com/channel/UCf_dVNrilcT0V2R--HbYpMA">
        <img src="https://img.shields.io/badge/πππππππππ-red?logo=youtube" width="200">
  </p>
<hr>
  
## About This Bot

<b><a href="https://www.github.com/Aadhi000" title="Dollow">Follow Me For Updates</a></b>

<p align="center">
    <a href="https://github.com/Aadhi000/File-To-Link">
        <img src="https://www.flaticon.com/premium-icon/icons/svg/2626/2626281.svg" height="100" width="100" alt="Telegram Logo">
    </a>
</p>
<p align='center'>
    This bot will give you stream links for Telegram files without the need of waiting till the download completes
</p>

## How to make your own

Either you could locally host or deploy on [Heroku](https://heroku.com)

### Deploy on Heroku

Press the below button to Fast deploy on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Aadhi000/File-To-Link)


πFeatures<p>
π₯Superfastβ‘οΈ download and stream links.<br>
π₯No ads in generated links.<br>
π₯Superfast interface.<br>
π₯Along with the links you also get file information like name,size ,etc.<br>
π₯Updates channel Support.<br>
π₯Mongodb database support for broadcasting.<br>
π₯Password Protection.<br>
π₯User Freindly Interface.<br>
π₯Ping check.<br>
π₯User DC Check.<br>
π₯Real time CPU , RAM , Internet usage. <br>
π₯Custom Domain support. <br>
π₯All unwanted code removed. <br>
π₯A lot more tired of writing check out by deploying it. 
</details>
<details>
  <summary><b>Host it on VPS Locally :</b></summary>


```py
git clone https://github.com/adarsh-goel/Filestreambot-pro
cd Filestreambot-pro
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
python3 -m Adarsh
```

and to stop the whole bot,
 do <kbd>CTRL</kbd>+<kbd>C</kbd>

Setting up things

If you're on Heroku, just add these in the Environmental Variables
or if you're Locally hosting, create a file named `config.env` in the root directory and add all the variables there.
An example of `config.env` file:

```py
API_ID=12345
API_HASH=esx576f8738x883f3sfzx83
BOT_TOKEN=55838383:yourtbottokenhere
BIN_CHANNEL=-100
PORT=8080
FQDN=your_server_ip
OWNER_ID=your_user_id
DATABASE_URL=mongodb_uri
```
  </details>

<details>
  <summary><b>Vars and Details :</b></summary>

`API_ID` : Goto [my.telegram.org](https://my.telegram.org) to obtain this.

`API_HASH` : Goto [my.telegram.org](https://my.telegram.org) to obtain this.
  
`MY_PASS` : Bot PASSWORD

`BOT_TOKEN` : Get the bot token from [@BotFather](https://telegram.dog/BotFather)

`BIN_CHANNEL` : Create a new channel (private/public), add [@missrose_bot](https://telegram.dog/MissRose_bot) as admin to the channel and type /id. Now copy paste the ID into this field.
  
`OWNER_USERNAME` : U should be knowing it afterall it's your username dont remember ? it just go to settings!

`OWNER_ID` : Your Telegram User ID

`DATABASE_URL` : MongoDB URI for saving User IDs when they first Start the Bot. We will use that for Broadcasting to them. I will try to add more features related with Database. If you need help to get the URI you can click on logo below!

[![Deploy k mongo](https://telegra.ph/file/fd68906852c71fdd68bef.jpg)](https://www.youtube.com/watch?v=HhHzCfrqsoE)

 Option Vars

`UPDATES_CHANNEL` : Put a Public Channel Username, so every user have to Join that channel to use the bot. Must add bot to channel as Admin to work properly.

`BANNED_CHANNELS` : Put IDs of Banned Channels where bot will not work. You can add multiple IDs & separate with <kbd>Space</kbd>.

`SLEEP_THRESHOLD` : Set a sleep threshold for flood wait exceptions happening globally in this telegram bot instance, below which any request that raises a flood wait will be automatically invoked again after sleeping for the required amount of time. Flood wait exceptions requiring higher waiting times will be raised. Defaults to 60 seconds.

`WORKERS` : Number of maximum concurrent workers for handling incoming updates. Defaults to `3`

`PORT` : The port that you want your webapp to be listened to. Defaults to `8080`

`WEB_SERVER_BIND_ADDRESS` : Your server bind adress. Defauls to `0.0.0.0`

`NO_PORT` : If you don't want your port to be displayed. You should point your `PORT` to `80` (http) or `443` (https) for the links to work. Ignore this if you're on Heroku.

`FQDN` :  A Fully Qualified Domain Name if present. Defaults to `WEB_SERVER_BIND_ADDRESS` </details>

<details>
  <summary><b>How to Use :</b></summary>

:warning: **Before using the  bot, don't forget to add the bot to the `BIN_CHANNEL` as an Admin**
 
`/start` : To check if the bot is alive or not.

To get an instant stream link, just forward any media to the bot and boom, its fast af.
  
![image](https://user-images.githubusercontent.com/88939380/145798095-3cdad108-96b0-4391-a540-cad144d6b864.png)


### Channel Support
Bot also Supported with Channels. Just add bot Channel as Admin. If any new file comes in Channel it will edit it with **Get Download Link** Button. </details>

### Credits : 

- [Adarsh Goel_(me)](https://github.com/adarsh-goel)
- [DeekshithSH](https://github.com/DeekshithSH) 
- Everyone In This Journey !

<b>α΄α΄α΄ α΄Κα΄α΄α΄Κ βΊβΊ [α΄α΄α΄ΚΙͺ](https://telegram.dog/AboutAadhi) | [ΙͺΙ΄sα΄α΄Ι’Κα΄α΄](https://www.instagram.com/aadhi.xr/) | [Ι’Ιͺα΄Κα΄Κ](GitHub.com/Aadhi000)</b>                                                                                                                                                                                    
<b>α΄Κα΄Ι΄Ι΄α΄Κ βΊβΊ [α΄α΄‘ α΄α΄α΄α΄α΄α΄α΄’](https://t.me/MWUpdatez)</b>
