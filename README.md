# eetch_bot

A Telegram bot for AI-powered, private romantic and sexual challenges for couples and groups—delivered via Telegram.

## Features
- /start — Welcome message
- /about — Short description
- /profile — View your profile (challenges completed)
- /challenge — Get a random challenge

## Setup
1. Clone this repo.
2. Run `npm install` in the `bot` directory.
3. Create a `.env` file with:
   ```
   TELEGRAM_BOT_TOKEN=your_telegram_bot_token
   ```
4. Start the backend API (see `/backend/index.js` for a simple Express server).
5. Run the bot:
   ```
   node bot.js
   ```

## Requirements
- Node.js
- Telegram Bot API token (get from @BotFather)
- Backend API running on http://localhost:4000

## Example backend
See `/backend/index.js` for a simple Express API to handle user profiles and challenges.

---

**Note:** Do not commit your real `.env` file or API token to public repositories.
