# WH DrawFib Pro MT5 ReadMe

## Description
WH DrawFib Pro MT5 is a Forex trading expert advisor that utilizes Fibonacci levels to identify trend reversals and make profitable trading decisions. It is designed to provide valuable trend insights by displaying the history of Highs and Lows on a user-friendly interface. This expert advisor is developed by Forex Robot Easy Team.

For detailed reviews and trading results of this product, please visit our website: [WH DrawFib Pro MT5 Review](https://forexroboteasy.com/forex-robot-review/wh-drawfib-pro-mt5-review-unbiased-forex-software-analysis/). Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## How it Works
The WH DrawFib Pro MT5 expert advisor is built using MQL5 programming language and is designed to run on the MetaTrader 5 platform. The code consists of several functions that are executed in a specific order to perform the trading operations.

### Initialization
Upon initialization, the expert advisor sets the Fibonacci levels for trend reversal identification. The levels are defined as `fibLevel1` (0.382) and `fibLevel2` (0.618). Other necessary components and indicators are also initialized in this function.

### Tick Function
The tick function is the main function that is executed on each tick of the market. It first identifies the current market trend. Then, it checks for trend reversal using the Fibonacci levels by calling the `IsTrendReversal()` function.

### Trend Reversal
The `IsTrendReversal()` function implements the logic to check for trend reversal using Fibonacci levels. It returns true if a trend reversal is identified.

### Display History
If a trend reversal is identified, the expert advisor proceeds to display the history of Highs and Lows by calling the `DisplayHistory()` function. This function shows the historical data to provide valuable trend insights.

### Trading Decisions
After displaying the history, the expert advisor makes profitable trading decisions based on the analysis. The logic for making trading decisions is implemented in the `MakeTradingDecisions()` function. It executes necessary trading functions to support the algorithm.

### Deinitialization
Upon deinitialization, the expert advisor performs clean up and releases any resources that were used during its execution.

## Usage
To use the WH DrawFib Pro MT5 expert advisor, follow these steps:
1. Download and install the MetaTrader 5 platform.
2. Copy the expert advisor code into a new MQL5 script file.
3. Compile the script to generate the expert advisor executable file.
4. Launch the MetaTrader 5 platform and open a chart for the desired currency pair.
5. Attach the expert advisor to the chart by dragging and dropping the executable file onto the chart.
6. Configure the expert advisor settings according to your preferences.
7. Start the expert advisor and it will automatically execute trading decisions based on the identified trend reversals.

Please note that trading with expert advisors involves risks, and it is recommended to thoroughly test the expert advisor on a demo account before using it in a live trading environment.

## Support and Contact
For any issues or queries related to the WH DrawFib Pro MT5 expert advisor, please contact the official developer through the MQL5 platform. ForexRobotEasy is not the official developer of this product, and we only provide a sample code for reference.

For detailed reviews and trading results of this product, please visit our website: [WH DrawFib Pro MT5 Review](https://forexroboteasy.com/forex-robot-review/wh-drawfib-pro-mt5-review-unbiased-forex-software-analysis/).
