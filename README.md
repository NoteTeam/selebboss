<h2 align="centre">๐ต SELEB BOSS  MUSIC BOT</h2>

### ๐งช Get STRING_SESSION from below:

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@levinalab/StringSession#main.py)

### ๐ History

[![Mentioned in Awesome Python](https://awesome.re/mentioned-badge.svg)](https://github.com/levina-lab/VeezMusic)

## Features ๐ฎ

- Thumbnail Support
- Playlist Support
- Showing track names when skipping
- Youtube, Local playback support
- Settings panel
- Control with buttons
- Userbot auto join
- Channel Music Play
- Keyboard selection support for youtube play
- Lyrics Scrapper
- Unlimited Queue
- Broadcast Bot
- Statistic Collector
- Group Tools (ban/unban/mute/unmute)
- Block / Unblock (restrict user for using your bot)

## Commands ๐ 

- `/play <song name>` - play song you requested
- `/playlist` - Show now playing list
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/vsong <song name>` - download videos you want quickly
- `/lyric <song name>` - lyrics scrapper
- `/vk <song name>` - generate song without download

#### Admins Only ๐ทโโ๏ธ
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/musicplayer on` - to disable music player in your group
- `/musicplayer off` - to enable music player in your group
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/reload` - Refresh admin list
- `/uptime` - check the bot uptime status
- `/ping` - check the bot ping status
- `/auth` - authorized people to access the admin commands
- `/deauth` - deauthorized people to access the admin commands
- `/control` - open the music player control panel

### Sudo User ๐งโโ๏ธ
- `/stats` - see the bot statistic
- `/pmpermit on | off` turn on/off the assistant pmpermit
- `/userbotleaveall` - order the assistant to leave all groups
- `/gcast` - send a broadcast message from the assistant

### Owner Only ๐จ๐ปโโ๏ธ
- `/broadcast` - send a broadcast message from the bot
- `/block` - block people for using your bot
- `/unblock` - unblock people you blocked for using your bot
- `/blocklist` - show the list of all people who's blocked for using your bot

### pm-permit ๐ฌ
- `.yes` - approve user for sending message to assistant
- `.no` - disapprove user for sending message to assistant

## ๐ Support Inline Search

## Heroku Deployment ๐
The easy way to host this bot, deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/NoteTeam/selebboss)

## VPS Deployment ๐ก

```sh
sudo apt update && apt upgrade -y
sudo apt install git curl python3-pip ffmpeg -y
pip3 install -U pip
curl -sL https://deb.nodesource.com/setup_16.x | bash -
sudo apt-get install -y nodejs
npm i -g npm
git clone https://github.com/levina-lab/VeezMusic # Clone your repo.
cd VeezMusic
pip3 install -U -r requirements.txt
cp example.env .env #Use vim to edit ENVs
vim .env #Fill up your ENVs ( Steps press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file.)
python3 main.py # Run the bot
```
