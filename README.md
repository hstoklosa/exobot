# exobot (experimental)

ExoBot is an open-source discord bot, and it's aim is to provide the essential as well as customisable tools that can be used on any server by both users and administrators.

## 🔍 Current Features

- Welcome/Join Message
- Customisable Reaction Roles
- Custom Help Command
- Info Commands (Server, Roles, User)
- Fun Commands (Meme, RPS)
- Misc Commands (Github, Osu)
- Poll & Ranking System (MySQL)
- Music Player (Looping & Queuing)

## Installation

1. Clone the repository

   ```
   git clone git@github.com:hstoklosa/exobot.git && cd exobot
   ```

2. Create a virtual environment and enter it

   ```
   python3 -m venv bot-env

   source bot-env/bin/activate
   ```

3. Install dependencies

   ```
   pip install -r requirements.txt
   ```

4. Run the bot

   ```
   python main.py
   ```

## 🖥️ Technologies

These technologies are required to run the bot.

- [Python 3.10](https://www.python.org/downloads/)
- [Project Packages](https://github.com/imexotic/ExoBot/blob/main/requirements.txt)
  - discord.py + jishaku
  - mysql-connector-python
  - shortuuid
  - aiohttp
  - asyncio
  - youtube-dl

## 📝 License

H. Stoklosa - hubert.stoklosa23@gmail.com

Distributed under the MIT license. See `LICENSE` for more information.

[https://github.com/hstoklosa](https://github.com/hstoklosa)
