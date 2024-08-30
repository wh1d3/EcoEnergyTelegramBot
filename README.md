# EcoEnergy Telegram Bot

EcoEnergy is a Telegram bot that helps users manage their profiles and view the electricity outage schedule. The bot allows you to create profiles, log in, view profile data, and receive up-to-date information about the outage schedule.

![Blackout schedule](https://i.imgur.com/SLrkv1I.png)

## Main functions

1. **Profile registration**.
   - Create a new profile with a login, password, and outage queue.
   - Automatically logs in after creating a profile.

2. **Login**.
   - Log in with a login and password.
   - Account blocking for 15 minutes after three failed login attempts.

3. **View profile**.
   - Use the `/myprofile` command to view profile information (login and disconnect queue).

4. **View outage schedule**.
   - The `/energy` command sends an image of the power outage schedule with a caption containing the current date.

5. **Main menu**.
   - The `/start' command displays a menu with options for creating a profile and logging in.

6. **Additional commands**.
   - `/site`: Provides a link to a website.
   - `/help`: Provides information about available commands and how to use them.

## Technologies and libraries

- **Python**: Programming language for writing a bot.
- **Python-telegram-bot**: Library for integration with the Telegram API.
- **SQLite**: A lightweight database for storing user information.
- **Datetime**: For working with dates and time.

## Requirements

- Python 3.8+.
- Libraries: `python-telegram-bot`, `datetime`, `qlite3`.

## List of commands

- `/start`: Displays a menu with options for creating a profile and logging in.
- `/myprofile`: Displays information about your profile.
- `/energy`: Displays an image of the power outage schedule.
- `/site`: Link to a website.
- `/help`: Provides information about available commands and how to use them.

## How to run.

1. Clone the repository:
   ```bash
   git clone https://github.com/wh1d3/EcoEnergyTelegramBot.git
   ```
2. Change to the project directory:
   ```bash
   cd EcoEnergyTelegramBot
   ```
3. Install the libraries:
   ```bash
   pip install python-telegram-bot
   ```
4. Replace BOT_TOKEN with your real Telegram bot token in the main.py file.
5. Run the bot:
   ```bash
   python main.py
   ```
6. In case of problems with the database, delete the old one and run the generator of the new one:
   ```bash
   python init_db.py
   ```

# Contacts
For any questions or suggestions, please contact us via Telegram
