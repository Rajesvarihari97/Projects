# Crypto Analysis Bot

This repository contains a simplified cryptocurrency trading bot built with Python and the [CCXT](https://github.com/ccxt/ccxt) library. The bot is designed to fetch market data, analyze trends, and execute trades based on defined strategies.

>  **Disclaimer**: This code is for educational and demonstration purposes only. API keys and secrets have been redacted. Do not use this in a production environment without thorough testing and proper risk management.

---

##  Features

- Connects to multiple crypto exchanges via `ccxt`
- Fetches historical candlestick (OHLCV) data
- Implements basic trading strategies
- Calculates indicators (e.g., moving averages)
- Simulated trade execution logic

---

##  Technologies Used

- Python 3
- Pandas, NumPy
- CCXT (Crypto Exchange Trading Library)
- datetime and time modules


##  How It Works

1. Configure the exchange (API keys redacted).
2. Load historical data for a given symbol and timeframe.
3. Analyze the data and calculate indicators.
4. Project decisions to "buy", "sell", or "hold" based on strategy logic.
