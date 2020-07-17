# Simple Binance Trader

# Disclaimer
This is just a software, it's results are informed but they are not guranteed to earn you money. Be careful when trading and please be responsible

## Description
This is a simple binance trader that uses the REST api and sockets to allow automation or manipulation of account detail/data. The script which in the default configuration uses a basic MACD trading setup to trade. The script however is very customisable and you'll be able to configure it as you with via the help of the document in the usage section.

### Repository Contains:
- run.py : This is used to start/setup the bot.
- conditions.py : Here is where you write your conditions using python logic.
- TradeIndicators.py : This contains indicators that can be used by the bot.
- Core
  - botCore.py : Is used to manage the socket and trader as well as pull data to be displayed.
  - reqCheck.py : Checks rest requests.
  - restAPI.py : Makes calls to the rest API.
  - socketAPI.py : Makes a socket and manages incoming data. (NOTE: you will need the 'websocket_client' module)
  - trader.py : The main trader inchage or updating and watching orders.
  
### Setting File:
- "publicKey" = Public API key.
- "privateKey" = Private API key.
- "runType" = If the bot is run in test mode or not (Run in real mode ar your own risk, this script has not been exstensivly tested and may have issues.)
- "mainInterval" = The Time interval for candles.
- "traderCurrency" = The amount of btc allowed to share between every market.
- "markets" = The market you want to trade.

## Usage
To quickly install all the required modules use 'pip3 install -r requirements', this should install the modules for you.

To set up the bot and for any further detail please refer to the google doc link below:
https://docs.google.com/document/d/1W5Pzq3qJJrbG5ytKHeaaBoVxsyuFUKDvdE0bSxJqPDA/edit?usp=sharing

### Contact
Please if you find any bugs or issues contact me so I can improve.
EMAIL: m.efukohure@gmail.com
