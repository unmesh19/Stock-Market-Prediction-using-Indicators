# Stock Market Prediction Using Indicators

This project focuses on predicting stock market movements using key technical indicators. The analysis is divided into two parts: **long-term stock market prediction** and **short-term stock market prediction**, each leveraging different timeframes and indicators to generate actionable buy or sell signals. The project also provides a detailed explanation of the indicators used in the analysis, helping users understand how these indicators work and how they are applied to stock market prediction.

## Project Breakdown:

1. **Long Term Stock Market Prediction**:  
   The long-term prediction model uses historical stock data and key indicators like Simple Moving Averages (SMA), Exponential Moving Averages (EMA), Moving Average Convergence Divergence (MACD), and Relative Strength Index (RSI) to predict long-term trends. This part helps investors identify longer-term stock trends and make strategic investment decisions.

2. **Short Term Stock Market Prediction**:  
   The short-term prediction model focuses on recent stock data to make predictions about the next few days or weeks. Similar indicators (EMA, MACD, RSI) are used but with a focus on short-term price movements. This model provides actionable insights for traders looking to capitalize on short-term market fluctuations.

3. **Stock Market Indicators and Their Formulas**:  
   This part of the project explains the formulas behind the technical indicators used in the predictions. It provides clear definitions of SMA, EMA, MACD, and RSI, and how each of these indicators is calculated and interpreted in stock market analysis.

## Key Indicators Explained:
- **Simple Moving Average (SMA)**: Helps identify long-term trends by averaging stock prices over a specified period.
- **Exponential Moving Average (EMA)**: Similar to SMA but gives more weight to recent prices, making it more responsive.
- **Moving Average Convergence Divergence (MACD)**: Shows the relationship between two EMAs and helps identify potential changes in trend direction.
- **Relative Strength Index (RSI)**: Measures whether a stock is overbought or oversold, indicating potential reversal points.

## How It Works:
- The project fetches stock data using Yahoo Finance.
- Based on this data, the indicators (SMA, EMA, MACD, RSI) are calculated for long-term and short-term timeframes.
- Buy and sell signals are generated based on the values of these indicators:
  - **Long Term Signals**: Focus on overall trend direction and long-term buy/sell opportunities.
  - **Short Term Signals**: React to recent price movements and provide quick trading opportunities.

## Conclusion:
This project provides a comprehensive analysis of stock price movements using widely used technical indicators, offering tools for both long-term investors and short-term traders. By understanding and applying these indicators, users can gain valuable insights into market trends and make more informed decisions in stock trading.
