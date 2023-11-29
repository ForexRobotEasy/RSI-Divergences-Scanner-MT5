# RSI Divergences Scanner MT5
This code is a sample implementation of an RSI (Relative Strength Index) Divergences Scanner for MetaTrader 5 (MT5). It scans multiple currency pairs and timeframes for RSI divergences, which can be potential trading opportunities.

## Developer's Site
For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/rsi-divergences-scanner-mt5-review-and-deal-alert/). Please note that ForexRobotEasy is not the official developer of this product. They only provide reviews and information about the product. To find the official developer of this product, please use MQL5.

## How it Works
1. The code includes necessary libraries for trading and technical indicators.
2. Constants are defined, including the size of arrays for symbols and timeframes, RSI period, and overbought/oversold levels.
3. Objects for trading and indicators are initialized.
4. An array of symbols and timeframes is defined.
5. The `OnTick()` function is the main function that is executed on each tick of the market.
6. The code iterates over each symbol in the symbols array and each timeframe in the timeframes array.
7. For each symbol and timeframe, the RSI value is calculated using the `iRSI()` function from the indicators library.
8. The code checks for RSI divergences using the `IsRSIDivergence()` function.
9. If a divergence is found, the symbol, timeframe, and RSI value are printed, and trading functions are executed using the `ExecuteTradingFunctions()` function.
10. The `IsRSIDivergence()` function checks for bullish and bearish RSI divergences based on the current and previous RSI values.
11. The `ExecuteTradingFunctions()` function is a placeholder where you can implement your own trading functions based on the RSI divergence.
12. The `OnInit()` function is executed during the initialization of the program and initializes the trade object.
13. The `OnDeinit()` function is executed during the deinitialization of the program and performs necessary clean-up operations.
14. The `OnStart()` function is executed when the program starts and contains the main loop of the program where necessary operations are performed.

## Product Description
The RSI Divergences Scanner MT5 is a powerful tool for traders looking to identify potential trading opportunities based on RSI divergences. The code provided is a sample implementation that can be used as a starting point for building a customized trading system.

Key Features:
- Scans multiple currency pairs and timeframes for RSI divergences
- Provides real-time alerts and notifications when a divergence is detected
- Can be customized with additional trading functions to execute trades automatically
- Works on the MetaTrader 5 platform, a popular trading platform used by traders worldwide

Please note that this code is provided as a sample and is not the official product developed by Forex Robot Easy. To find the official developer and obtain the full version of the product, please visit the [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/rsi-divergences-scanner-mt5-review-and-deal-alert/) website or use MQL5.
