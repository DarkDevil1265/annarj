# ANNA_BEN_BOT
Very Sempil Bot Auto Filter bot
##[![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=welcome+To+𝑨𝑵𝑵𝑵𝑨-𝑩𝑬𝑵-𝑭𝑰𝑳𝑻𝑬𝑹-𝑩𝑶𝑻!;created+by+𝑻𝑬𝑨𝑴+𝑨𝑵𝑵𝑨+𝑩𝑬𝑵!;A+simple+autofilter+Bot!;Auto+filter+with+double+button!;start+message+with+pic!;and+all+futures!)
</p>
# 𝐂𝐋𝐈𝐂𝐊 𝐁𝐄𝐋𝐎𝐖 𝐈𝐌𝐀𝐆𝐄 𝐓𝐎 𝐃𝐄𝐏𝐋𝐎𝐘👇👇👇


[![Deploy](https://telegra.ph/file/d35d46c4b9f7bfc79564e.jpg)](https://heroku.com/deploy?template=https://github.com/Lallu-lallus/anna-ben-repo)

- [x] Auto Filter
- [x] Manuel Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Fun mode
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel



<h3 align="center">ℂ𝕆ℕ𝕋𝔸ℂ𝕋<img align="center" src="https://github.com/PANDITHAN/PANDITHAN/blob/main/assets/Handshake.gif" height="33px" /></h3>
<p align="center">
<a href="https://t.me/pro_editor_tg"><img alt="Telegram" src="https://img.shields.io/badge/𝙳𝙴𝚅 1-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/></a>
<a href="https://t.me/PANDITHAN_SIR"><img alt="Telegram" src="https://img.shields.io/badge/𝙳𝙴𝚅 2-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/></a>
</p>



## Installation

















## DEPLOY ON HEROKU
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Lallu-lallus/anna_ben)


#Hard Way

```bash
# Create virtual environment
python3 -m venv env

# Activate virtual environment
env\Scripts\activate.bat # For Windows
source env/bin/activate # For Linux or MacOS

# Install Packages
pip3 install -r requirements.txt

# Edit info.py with variables as given below then run bot
python3 bot.py
```
Check [`sample_info.py`](sample_info.py) before editing [`info.py`](info.py) file

## Variables

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* Check [info.py](https://github.com/EvamariaTG/evamaria/blob/master/info.py) for more

## Note
* Currently the [API used](http://www.omdbapi.com) in this repo is allowing 1000 requests per day. [You may not get posters if its crossed](https://t.me/ThankTelegram/910168). 
Once a poster is fetched from OMDB , poster is saved to DB to reduce duplicate requests.

## Admin commands
```
channel - Get basic infomation about channels
total - Show total of saved files
delete - Delete file from database
index - Index all files from channel.
logger - Get log file
```

## Tips
* You can use `|` to separate query and file type while searching for specific type of file. For example: `Avengers | video`
* If you don't want to create a channel or group, use your chat ID / username as the channel ID. When you send a file to a bot, it will be saved in the database.



## Thanks to 
* [Pyrogram](https://github.com/pyrogram/pyrogram)
* Original [Repo](https://github.com/Lallu-lallus/ALPHA_IMDB_BOT)


## Support
Contact Me On [Telegram](https://t.me/RJMALLU)

[Update Channel](https://t.me/Team_annaben)

## License
Code released under [The GNU General Public License](LICENSE).
## credit 🤠
https://t.me/PANDITHAN_SIR




[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FDarkDevil1265%2FRailwaywork&envs=ADMINS%2CAPI_HASH%2CAPI_ID%2CBOT_TOKEN%2CDATABASE_NAME%2CDATABASE_URI%2CLOG_CHANNEL%2CPICS%2CSINGLE_BUTTON%2CSUPPORT_CHAT%2CUSE_CAPTION_FILTER%2CCUSTOM_FILE_CAPTION%2CCOLLECTION_NAME&ADMINSDesc=Username+or+ID+of+Admin.+Separate+multiple+Admins+by+space.&API_HASHDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&API_IDDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&BOT_TOKENDesc=Your+bot+token&DATABASE_NAMEDesc=Name+of+the+database+in+mongoDB.+&DATABASE_URIDesc=mongoDB+URI.+Get+this+value+from+https%3A%2F%2Fwww.mongodb.com&LOG_CHANNELDesc=Bot+Logs%2CGive+a+channel+id+with+-100xxxxxxx&PICSDesc=Pics+for+bot&SINGLE_BUTTONDesc=choose+b%2Fw+single+or+double+buttons+%28single+button-+True%2C+Double+button-+false%29&SUPPORT_CHATDesc=Username+of+a+Support+Group+%2F+ADMIN.+%28+Should+be+username+without+%40+and+not+ID%29&USE_CAPTION_FILTERDesc=Whether+bot+should+use+captions+to+improve+search+results.+%28True+False%29&CUSTOM_FILE_CAPTIONDesc=File+name&COLLECTION_NAMEDesc=Files&USE_CAPTION_FILTERDefault=False&CUSTOM_FILE_CAPTIONDefault=%40Cine_makotta&COLLECTION_NAMEDefault=Telegram_files&referralCode=LBlqTu)
