# Candlestick Screener

Takes price charts of stocks from the S&P 500 and runs candle stick patterns to indicate bullish or bearish events.

- patterns.py holds all the candle stick patterns used
- consolidationbreakoutscreener.py scans for breakout and colidatation stocks around 2%
- app.py leverages flask to create the screeners that pull Finviz charts
