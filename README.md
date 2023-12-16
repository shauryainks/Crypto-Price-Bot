Crypto-Price-Bot: Track Your Crypto in Discord ✨
** Stay on top of your favorite coin's price movements right in your Discord server!**

** Features:**

Track any cryptocurrency you want in your preferred fiat currency (USD by default).
Automatic updates every 5 minutes, keeping you in the loop.
See the current price, 24-hour change, and percentage change at a glance.
Emoji indicators: Green for up, red for down, skull for all-time low, party for all-time high!
(Optional) Customize the bot's roles based on price change (positive, neutral, negative).
‍♀️ (Optional) Change the bot's online status based on price change (online for up, idle for neutral, do not disturb for down).
** Files:**

bot.py: The brains of the operation, fetching data, crunching numbers, and updating the bot's info.
Procfile: A handy shortcut to run the bot with specific settings.
requirements.txt: Lists all the Python libraries needed to make this magic happen.
runtime.txt: Specifies the Python version to use (3.8.0 is recommended).
** Setting Up:**

Install the dependencies: Run pip install -r requirements.txt in your terminal.
Create a Discord bot: Head to the Discord Developer Portal and create a new bot. Remember to grab its token!
Configure the bot:
Edit Procfile: Replace {crypto-token-name} with your chosen cryptocurrency's symbol (e.g., btc for Bitcoin).
Update {Discord-Bot-Token} with your bot's token.
Feel free to tinker with other options in bot.py like the fiat currency and role names.
Run the bot: Open your terminal and run ./worker. That's it, your Discord server just got a crypto-savvy companion!
** Additional Notes:**

The bot uses CoinGecko's public APIs to fetch data.
For continuous operation, consider using a process manager like supervisor or pm2.
Need more information on Discord bots? Check out the official docs: https://discord.com/developers/docs/intro: https://discord.com/developers/docs/intro
** License:**

This project is under the MIT License. Feel free to use, modify, and share it as you wish, but please credit Shauryainks and include a copy of the license in any modified versions. Remember, respect for fellow developers builds a strong community!
