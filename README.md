# Telegram_bot-svatek

A Telegram bot for daily name day (svátky) notifications with automatic scheduling.

---

## Preview

This is what the message looks like when the bot sends it to your Telegram channel or chat every morning:

![Bot message preview](images/00.png)

---

## Setup & Installation

### 1. Prerequisites
To keep your sensitive data (tokens) safe from being exposed on GitHub, this script uses system environment variables. You will need:
*   **A Telegram Bot Token** (obtained from [@BotFather](https://t.me/BotFather))
*   **A Chat ID** (the ID of the chat or channel where the bot should send messages)

### 2. Automatic Scheduling (Cron)

To make the bot send messages automatically every day, add it to your Linux system scheduler (`cron`).

1. Open the cron configuration for your current user:
   ```bash
   crontab -e
