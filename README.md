# Stock Market Prediction Using Indicators

This project focuses on stock market prediction by analyzing historical stock data and applying various technical indicators. It includes two separate analysis models: one for **short-term** predictions and another for **long-term** predictions, each utilizing different indicators to generate actionable buy and sell signals. Both models use Python and rely on key indicators such as Moving Averages, MACD, and RSI to make informed decisions about the stock market.

## Project Overview:
The project consists of two main notebooks:
1. **Short Time Stock Market Prediction using Indicators.ipynb**
   - Focuses on predicting stock movements over short time periods (e.g., daily to weekly trends).
   - Uses **Exponential Moving Averages (EMA)**, **MACD**, and **RSI** as key indicators.
   - The model generates buy and sell signals based on the relationship between stock price and the calculated indicators.
   
2. **Long Term Stock Market Prediction using Indicators.ipynb**
   - Aimed at predicting long-term stock market trends (e.g., weeks to months).
   - Calculates **Simple Moving Averages (SMA)**, **Exponential Moving Averages (EMA)**, **MACD**, and **RSI**.
   - This model is designed for investors looking to track long-term trends and make investment decisions accordingly.

### Key Indicators Explained:
The project relies on the following technical indicators for stock market analysis:

1. **Simple Moving Average (SMA)**: The average of the stock’s closing prices over a specified period. Used to identify the general direction of the market trend.
2. **Exponential Moving Average (EMA)**: Similar to SMA but gives more weight to recent prices. It reacts more quickly to price changes.
3. **Moving Average Convergence Divergence (MACD)**: The difference between the 12-day and 26-day EMAs. It helps identify changes in momentum and trend.
4. **Relative Strength Index (RSI)**: Measures the speed and change of price movements, helping to identify overbought or oversold conditions in a stock.

### How It Works:
- **Data Fetching**: Stock data is fetched using the `yfinance` library, which allows easy access to historical data from Yahoo Finance.
- **Indicator Calculation**: For both short-term and long-term predictions, the respective technical indicators (EMA, SMA, MACD, RSI) are calculated.
- **Signal Generation**:
  - **Buy Signal**: Indicates a favorable buying opportunity.
  - **Sell Signal**: Indicates a potential point to sell the stock or avoid further investments.
  
### Features:
- **Short-Term Model**: Focuses on short-term price movements, typically ranging from daily to weekly, ideal for traders.
- **Long-Term Model**: Focuses on identifying long-term trends, useful for investors with a longer time horizon.
- **Visualizations**: Interactive visualizations of stock data, moving averages, MACD, and RSI to help users better understand trends and signals.

### Prerequisites:
- Python 3.x
- Required libraries:
  - `yfinance`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `plotly`

### How to Run:
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/stock-market-prediction.git
   ```
2. Install the necessary libraries:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebooks:
   - **Short Time Stock Market Prediction using Indicators.ipynb**
   - **Long Term Stock Market Prediction using Indicators.ipynb**
4. Run the code cells to analyze stock data and generate buy/sell signals.

### Conclusion:
This project provides tools to analyze both short-term and long-term stock market movements by applying popular technical indicators. It is a helpful tool for both short-term traders looking to capitalize on quick price movements and long-term investors interested in tracking broader market trends.
