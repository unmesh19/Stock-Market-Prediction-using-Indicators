# Stock Market Prediction Using Indicators

This project focuses on stock market prediction by analyzing historical stock data and applying various technical indicators. It includes two separate analysis models: one for **short-term** predictions and another for **long-term** predictions, each utilizing different indicators to generate actionable buy and sell signals. Both models use Python and rely on key indicators such as Moving Averages, MACD, RSI, and others to make informed decisions about the stock market.

---

## **Project Overview**:
The project consists of two main notebooks:
1. **Short Time Stock Market Prediction using Indicators.ipynb**  
   - Focuses on predicting stock movements over short time periods (e.g., daily to weekly trends).  
   - Uses **Exponential Moving Averages (EMA)**, **MACD**, and **RSI** as key indicators.  
   - The model generates buy and sell signals based on the relationship between stock price and the calculated indicators.

2. **Long Term Stock Market Prediction using Indicators.ipynb**  
   - Aimed at predicting long-term stock market trends (e.g., weeks to months).  
   - Calculates **Simple Moving Averages (SMA)**, **Exponential Moving Averages (EMA)**, **MACD**, and **RSI**, along with additional indicators such as Bollinger Bands and OBV.  
   - This model is designed for investors looking to track long-term trends and make investment decisions accordingly.

---

## **Key Indicators Explained**:
The project relies on the following technical indicators for stock market analysis:

1. **Simple Moving Average (SMA)**:  
   - Calculates the average of the stock’s closing prices over a specified period.  
   - Used to identify the general direction of the market trend.  

2. **Exponential Moving Average (EMA)**:  
   - Similar to SMA but gives more weight to recent prices.  
   - Reacts more quickly to price changes, making it suitable for short-term trend detection.

3. **Moving Average Convergence Divergence (MACD)**:  
   - Represents the difference between the 12-day and 26-day EMAs.  
   - Helps identify changes in momentum and trend direction.  

4. **Relative Strength Index (RSI)**:  
   - Measures the speed and change of price movements.  
   - Used to identify overbought (RSI > 70) or oversold (RSI < 30) conditions in a stock.  

5. **Bollinger Bands**:  
   - Consists of a middle SMA line and two bands (upper and lower) based on standard deviation.  
   - Useful for identifying periods of high or low volatility and potential overbought or oversold conditions.

6. **On-Balance Volume (OBV)**:  
   - Tracks cumulative volume flow relative to price changes.  
   - Indicates the strength of a trend by showing whether volume supports the price movement.  

7. **Parabolic SAR (PSAR)**:  
   - A trend-following indicator used to identify potential reversals.  
   - Provides stop-loss levels, particularly useful in trending markets.  

8. **Short-Term RSI**:  
   - Similar to the standard RSI but calculated over a shorter period (e.g., 9 periods).  
   - Offers a quicker response to price movements, making it suitable for short-term predictions.  

9. **Bollinger Band Width**:  
   - Measures the distance between the upper and lower Bollinger Bands.  
   - A wider band indicates higher volatility, while a narrower band suggests lower volatility.  

10. **MACD Signal Line**:  
    - The EMA of the MACD values (typically over 9 periods).  
    - Helps smooth out MACD values for easier identification of crossovers.

---

## **How It Works**:
- **Data Fetching**: Stock data is fetched using the `yfinance` library, which allows easy access to historical data from Yahoo Finance.  
- **Indicator Calculation**: For both short-term and long-term predictions, the respective technical indicators (SMA, EMA, MACD, RSI, Bollinger Bands, and OBV) are calculated.  
- **Signal Generation**:  
  - **Buy Signal**: Indicates a favorable buying opportunity when certain conditions are met (e.g., RSI is low, MACD crosses above the signal line).  
  - **Sell Signal**: Indicates a potential point to sell the stock or avoid further investments.  

---

## **Features**:
- **Short-Term Model**:  
  - Focuses on short-term price movements, typically ranging from daily to weekly.  
  - Ideal for traders looking to capitalize on rapid market changes.

- **Long-Term Model**:  
  - Focuses on identifying broader market trends over weeks to months.  
  - Useful for long-term investors.  

- **Visualizations**:  
  - Includes interactive visualizations for stock prices, moving averages, MACD, RSI, and Bollinger Bands.  
  - Helps users interpret trends and buy/sell signals more effectively.  

---

## **Prerequisites**:
- Python 3.x  
- Required libraries:  
  - `yfinance`  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `plotly`

---

## **How to Run**:
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

---

## **Conclusion**:
This project provides tools to analyze both short-term and long-term stock market movements by applying popular technical indicators. It is a helpful resource for traders and investors to make informed decisions, whether aiming to profit from short-term fluctuations or track long-term trends.
