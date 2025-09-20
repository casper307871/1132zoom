# 1132zoom
Removes the 1132
# Telegram Cleanup Bot - One Click Deployment

## Setup

1. Replace `YOUR_TELEGRAM_BOT_TOKEN` in `bot.py` with your bot token.
2. Build and start the bot using Docker:

```bash
docker-compose up -d --build
```

3. The bot will start automatically. Use `/start` in Telegram to test.

## CI / Linting

- Pylint runs automatically via GitHub Actions.
- `.pylintrc` ignores minor style warnings.
