# Stock Market Indicators and Their Formulas

This document explains the commonly used technical indicators in stock market analysis. These indicators help traders and investors make informed decisions by interpreting the stock price movements and market trends.

## Key Indicators Explained:

### 1. **Simple Moving Average (SMA)**
- **Formula**:  
  \[
  \text{SMA} = \frac{P_1 + P_2 + \dots + P_n}{n}
  \]
  Where \( P_1, P_2, \dots, P_n \) are the closing prices over a specified period (e.g., 50 days, 200 days).
- **Explanation**:  
  The SMA is the average of the stock’s closing prices over a specific period. It smooths out the data to identify the direction of the trend.

### 2. **Exponential Moving Average (EMA)**
- **Formula**:  
  \[
  \text{EMA} = \text{(Today's Price} \times \text{(Multiplier)}) + \text{(Yesterday's EMA} \times (1 - \text{Multiplier}))
  \]
  Where the **Multiplier** is:
  \[
  \text{Multiplier} = \frac{2}{n + 1}
  \]
  and \( n \) is the number of days in the time period (e.g., 12 or 26 days).
- **Explanation**:  
  EMA gives more weight to the latest prices and reacts more quickly to price changes than the SMA.

### 3. **Moving Average Convergence Divergence (MACD)**
- **Formula**:  
  \[
  \text{MACD} = \text{EMA(12)} - \text{EMA(26)}
  \]
- **Explanation**:  
  MACD shows the relationship between two EMAs (12-day and 26-day). It helps traders spot changes in the strength, direction, momentum, and duration of a trend.

### 4. **Relative Strength Index (RSI)**
- **Formula**:  
  \[
  \text{RSI} = 100 - \frac{100}{1 + RS}
  \]
  Where \( RS \) (Relative Strength) is:
  \[
  RS = \frac{\text{Average Gain over n periods}}{\text{Average Loss over n periods}}
  \]
  and \( n \) is typically 14 days.
- **Explanation**:  
  RSI measures the speed and change of price movements. It indicates whether a stock is overbought (>70) or oversold (<30).
