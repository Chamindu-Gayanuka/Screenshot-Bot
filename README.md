<p align="center" style="font-size: xx-large; font-weight: bolder;">
  Screenshot Bot
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=18&pause=1000&width=435&lines=A+powerful+Telegram+bot+that+lets+users+;extract+evenly+spaced+screenshots+;from+videos+(.mp4+and+.mkv%60);Built+using+Pyrogram%2C+FFmpeg%2C+MongoDB)](https://git.io/typing-svg)

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<p align="center">
  <img src="https://ik.imagekit.io/rmlbayysp/1749093968626-umzscreenshot_1sqLVi9F0.png" alt="umz rename bot" align="center" width="250" height="250" />
</p>

### Sample Bot ( Screenshot - Bot )

[umz screenshot gen bot](http://t.me/umzscreenshotgen_bot)

## 🚀 Features

- Accepts `.mp4` and `.mkv` files sent as video or document
- Allows user to select 1–20 evenly spaced screenshots
- Returns screenshots as a Telegram media group
- `/start`, `/help`, `/cancel`, `/stats`, and `/broadcast` commands
- Stores user data and stats in MongoDB
- Logs every request to a private log channel
- Admin-only `/broadcast` and `/stats` commands
- Docker-ready with health check endpoint

---

## 📚 Requirements

- Python 3.10+
- FFmpeg (included in Docker image)
- MongoDB (MongoDB Atlas or local)
- Telegram Bot Token
- Telegram API ID & Hash from [my.telegram.org](https://my.telegram.org)

---

## 📦 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Chamindu-Gayanuka/Screenshot-Bot.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure environment variables

```plaintext
API_ID = your_api_id
API_HASH = your_api_hash
BOT_TOKEN = your_bot_token
ADMIN_ID = your_telegram_user_id
MONGODB_URI = your_mongodb_uri
LOG_CHANNEL = -100xxxxxxxxxx  # Telegram Channel ID for logging
```


### 4. Bot Commands
```
start - Start the bot
help - Show instructions
cancel - Cancel the current upload
stats - Show usage stats (admin only)
broadcast - Broadcast a message to all users (admin)
```

## 🚀 Deployment
[![Deploy on Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/Chamindu-Gayanuka/Screenshot-Bot)

## 📝 Note
- Make sure to set the environment variables in your deployment platform.
- For local testing, you can run the bot using:

```bash
python bot.py
```


## ©️ License
This project is licensed under the MIT License. See the [𝙇𝙄𝘾𝙀𝙉𝙎𝙀]() file for details.

## 🙏 Acknowledgements
- [𝙋𝙮𝙧𝙤𝙜𝙧𝙖𝙢](https://docs.pyrogram.org/) for the Telegram bot framework
- [𝙁𝙁𝙢𝙥𝙚𝙜](https://ffmpeg.org/) for video processing
- [𝙈𝙤𝙣𝙜𝙤𝘿𝘽](https://www.mongodb.com/) for data storage
- [𝘿𝙤𝙘𝙠𝙚𝙧](https://www.docker.com/) for containerization

## ❣️ Special Thanks 👍
- [𝘾𝙝𝙖𝙢𝙞𝙣𝙙𝙪 𝙂𝙖𝙮𝙖𝙣𝙪𝙠𝙖](https://github.com/Chamindu-Gayanuka) for creating this bot ❤ ♥
- [𝙐𝙣𝙡𝙞𝙢𝙞𝙩𝙚𝙙 𝙈𝙤𝙫𝙞𝙚 𝙕𝙤𝙣𝙚](https://t.me/Unlimited_Movie_Zone) for the inspiration and support

## Last Updated
- `05-06-2025 09:30 AM`