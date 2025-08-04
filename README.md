# GBP Telegram Bot

## Overview
This project is a Telegram bot to post updates to Google Business Profiles using Google My Business API.

## Setup

1. Get your Google API credentials JSON (`credentials.json`) and place it here.
2. Rename `.env.example` to `.env` and put your Telegram Bot token there.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the bot:
   ```bash
   python3 bot.py
   ```
5. On first run, authenticate Google API via browser or manual auth URL.
6. Use Telegram commands `/post <text>` and `/allpost <text>`.

## Notes
- Keep your `credentials.json` and `token.json` secure.
- Use `.gitignore` to avoid committing secrets.
