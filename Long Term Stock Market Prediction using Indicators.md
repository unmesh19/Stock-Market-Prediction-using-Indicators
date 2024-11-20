# Long Term Stock Market Prediction using Indicators

This project predicts long-term stock market movements by analyzing historical stock data and calculating key technical indicators. The goal is to help investors make informed decisions by observing long-term trends and key patterns in stock prices.

## Features:
- Fetches historical stock data from Yahoo Finance.
- Uses technical indicators like Simple Moving Averages (SMA), Exponential Moving Averages (EMA), Moving Average Convergence Divergence (MACD), and Relative Strength Index (RSI).
- Generates buy and sell signals based on indicator values.
- Visualizes stock price movements, SMAs, EMAs, MACD, and RSI using interactive plots.

## Key Indicators Used:
1. **Simple Moving Average (SMA)**: 50-day and 200-day SMAs.
2. **Exponential Moving Average (EMA)**: 12-day and 26-day EMAs.
3. **Moving Average Convergence Divergence (MACD)**: Difference between the 12-day and 26-day EMAs.
4. **Relative Strength Index (RSI)**: Measures the speed and change of price movements.

## How It Works:
1. Select a company from a predefined list (e.g., Reliance Industries, TCS, Infosys, etc.).
2. The program fetches stock data for that company from Yahoo Finance starting from January 1, 2001, up to the current date.
3. Calculates technical indicators (SMA, EMA, MACD, RSI) based on the historical stock data.
4. Generates buy or sell signals based on the following conditions:
   - **Buy Signal**: When the stock price is above the 50-day SMA, MACD is above its signal line, and RSI is between 30 and 70.
   - **Sell Signal**: When the stock price is below the 50-day SMA, MACD is below its signal line, or RSI is above 70.
5. Displays graphs of the stock price, moving averages, and RSI for better visualization.

## Prerequisites:
- Python 3.x
- Required libraries:
  - `yfinance`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `plotly`

## Installation:
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/long-term-stock-market-prediction.git
   ```
2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```

3. Run the program:
   ```
   python long_term_stock_market_prediction.py
   ```

## Conclusion:
This tool helps in analyzing long-term stock data and making predictions based on historical trends, offering valuable insights for investment decisions.
