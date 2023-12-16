## Crypto-Price-Bot

**Tired of switching between tabs to track your favorite coin's price?**  Say goodbye to the hassle and hello to **Crypto-Price-Bot**, your friendly Discord companion who keeps you informed right where you need it! 

**Features:**

* **Track any cryptocurrency you want:** Bitcoin, Ethereum, Dogecoin, you name it! 
* **Real-time updates every 5 minutes:** Stay ahead of the market with lightning-fast data. ⚡
* **Clear and concise information:** See the current price, 24-hour change, and percentage change at a glance. 
* **Fun emoji indicators:** Green for up, red for down, skull for all-time low, and a party popper for all-time high! 
* **Customize the bot (optional):** Set up roles based on price change and adjust the online status for extra flair. 

**Files:**

* `bot.py`: The brains behind the operation, fetching data, crunching numbers, and keeping you informed. 
* `Procfile`: A handy shortcut to run the bot with your specific settings. 🪄
* `requirements.txt`: Lists all the libraries needed to make the magic happen. ✨
* `runtime.txt`: Tells the bot which Python version to use (3.8.0 recommended). 

**Setting Up:**

1. **Install the dependencies:** Run `pip install -r requirements.txt` in your terminal. 
2. **Create a Discord bot:** Head to the Discord Developer Portal and give your bot a name! Remember to grab its token. 
3. **Configure your settings:**
    * Edit `Procfile`: Replace `{crypto-token-name}` with your chosen coin's symbol (e.g., `btc`). 🪙
    * Update `{Discord-Bot-Token}` with your bot's secret token. 
    * Feel free to tweak other options in `bot.py` like the fiat currency and role names. 
4. **Run the bot:** Open your terminal and run `./worker`. That's it! Your Discord server just got a crypto-savvy friend. 

**Additional Notes:**

* The bot uses CoinGecko's public APIs for accurate data. 
* For continuous operation, consider using a process manager like supervisor or pm2. 
