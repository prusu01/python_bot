# Discord Music Bot

A simple Discord music bot written in Python using the discord.py library.
## Introduction

This Discord music bot is designed to connect to a voice channel, play a specified audio file, and perform a basic random number generation command.

## Features

- Connect to a voice channel
- Play a specified audio file
- Generate a random number within a specified range

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python (>=3.6)
- [discord.py](https://discordpy.readthedocs.io/en/stable/)
- [ffmpeg](https://ffmpeg.org/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/discord-music-bot.git
    cd discord-music-bot
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Configuration

1. Create a Discord bot and obtain the token.
2. Set the `BOT_TOKEN` environment variable:

    ```bash
    export BOT_TOKEN=your_bot_token_here
    ```
3. run the bot program
4. Invite the bot to your Discord server.
5. Use the following commands:

    - `!join`: Join the user's voice channel.
    - `!leave`: Leave the current voice channel.
    - `!play`: Play a predefined audio file.
    - `!roll <max_val>`: Generate a random number between 1 and the specified `<max_val>`.



