# 🗂️ Wasabi Storage Telegram Bot

A powerful Telegram bot integrated with **Wasabi Cloud Storage** — enabling seamless file upload, download, and streaming directly through Telegram. Built with Python and designed for reliability, security, and performance.

## 🚀 Features
- 4GB File Support — Upload and download large files via Telegram  
- Wasabi Cloud Integration — Secure and scalable storage with direct access links  
- Direct Streaming Links — Stream videos using MX Player, VLC, or any external player  
- Admin Panel — Manage users, monitor storage, and control access  
- URL Shortening Support — Optional feature for short download links  
- User-Friendly Commands — Simple interface with clear Telegram commands  
- .env Configuration — Easy environment variable setup for deployment

## ⚙️ Configuration
Create a `.env` file in your project root:

Telegram Bot Configuration
'''bash
API_ID=1234567
API_HASH=your_api_hash
BOT_TOKEN=your_bot_token
ADMIN_ID=123456789
WASABI_ACCESS_KEY=your_wasabi_access_key
WASABI_SECRET_KEY=your_wasabi_secret_key
WASABI_REGION=your-region
WASABI_BUCKET=your-bucket-name
WASABI_ENDPOINT=https://s3.wasabisys.com

## 🧰 Installation

Clone the Repository

git clone https://github.com/Mraprguild/Wasabistoragebotmain.git

cd Wasabistoragebotmain

Create a Virtual Environment

python -m venv venv
source venv/bin/activate # Linux/Mac
venv\Scripts\activate # Windows

Install Dependencies

pip install -r requirements.txt

Run the Bot

python bot.py


## 💬 Bot Commands
| Command | Description |
|----------|-------------|
| /start | Start the bot and view welcome message |
| /help | Show help and usage guide |
| /upload | Upload file to Wasabi storage |
| /download <file_id> | Download file from Wasabi |
| /list | Show all uploaded files |
| /admin | Open admin panel (admins only) |

## 🧾 Requirements
- Python 3.9+
- Telegram Bot Token (via [BotFather](https://t.me/BotFather))
- Wasabi Cloud Storage Account
- Required Python modules in `requirements.txt`

## ☁️ Deployment
You can deploy the bot on:
- Heroku  
- VPS / Dedicated Server  
- Railway / Render / Fly.io  

## 📜 License
This project is open-source under the **MIT License**.

## 💡 Credits
Developed by **Mraprguild** — integrating Telegram Bot API with Wasabi Cloud for efficient file management.
