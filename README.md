# RSS Bot Dashboard

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](package.json)

![Description](screenshots/screenshot01.png)

A Telegram bot dashboard that automatically fetches and forwards the latest cryptocurrency news from CoinDesk to your Telegram channels. Stay up-to-date with the crypto world by having fresh news delivered directly to your Telegram channels in real-time.

## Key Features

- Automatically fetches latest news from CoinDesk's RSS feed
- Forwards news articles to configured Telegram channels
- Easy-to-use dashboard for managing channel subscriptions
- Real-time news delivery
- Customizable posting frequency

## Prerequisites

- Node.js (LTS version recommended)
- Yarn package manager
- Telegram Bot Token (you can get this from [@BotFather](https://t.me/botfather))

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
SECRET=your_secret_key
SERVICE_NAME=your_service_name
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/TelegramBotDashboards/rss-bot.git
cd rss-bot
```

2. Install dependencies:

```bash
yarn install
```

## Authentication

The dashboard comes with a default administrator account:

- Username: `admin`
- Password: `admin`

**Important**: For security purposes, it is strongly recommended to change these credentials after your first login.

## Building the Application

To build the application, run:

```bash
yarn build
```

## Running the Application

To start the server, run:

```bash
yarn start
```

## Development

To run the application in development mode:

```bash
yarn dev
```

## Preview

To preview production version

```bash
yarn preview
```

## Environment Variables Description

- `TELEGRAM_BOT_TOKEN`: Your Telegram bot token obtained from BotFather
- `SECRET`: A secret key used for securing your application
- `SERVICE_NAME`: The name of your service instance

## Security Notice

Never commit your `.env` file to version control. Make sure it's included in your `.gitignore` file.
