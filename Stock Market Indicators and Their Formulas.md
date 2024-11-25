# Stock Market Indicators and Their Formulas

This document provides an overview of key technical indicators used in stock market analysis. These indicators help traders and investors interpret stock price movements and market trends effectively.

---

## **Key Indicators**

### 1. **Simple Moving Average (SMA)**
- **Formula**:  

  SMA = (P_1 + P_2 + . . . + P_n)/n
  
  Where:  
  P_1, P_2,..., P_n are the closing prices over n periods.

- **Explanation**:  
  The SMA calculates the average of closing prices over a specific time period, helping smooth out price data to reveal the underlying trend.

---

### 2. **Exponential Moving Average (EMA)**
- **Formula**:  

  \text{EMA} = ((Today's Price) x Multiplier) + ((Yesterday's EMA) x (1 - Multiplier))
 
  Where:  
  - **Multiplier**:  
    
    Multiplier = 2/(n + 1)
  
    n is the number of periods.

- **Explanation**:  
  EMA assigns more weight to recent prices, making it more responsive to price changes than SMA.

---

### 3. **Moving Average Convergence Divergence (MACD)**
- **Formula**:  

  MACD = EMA(Short Period) - EMA(Long Period)
   

- **Explanation**:  
  MACD reveals the relationship between two EMAs, helping traders identify trend direction and momentum. A signal line (EMA of MACD values) is often used to generate buy or sell signals.

---

### 4. **Relative Strength Index (RSI)**
- **Formula**:  
  
  RSI = 100 - 100/(1 + RS)
    
  Where:  
  
  RS = (Average Gain over n periods)/(Average Loss over n periods)
    
  n is typically 14 periods.

- **Explanation**:  
  RSI measures the speed and magnitude of price movements, indicating overbought (RSI > 70) or oversold (RSI < 30) conditions.

---

### 5. **Bollinger Bands**
- **Formula**:  
  - **Middle Band**: SMA of closing prices (e.g., 20-period SMA).  
  - **Upper Band**:  

  - Upper Band = Middle Band + (2 x Standard Deviation)

  - **Lower Band**:  

  - Lower Band = Middle Band - (2 x Standard Deviation)

- **Explanation**:  
  Bollinger Bands help identify price volatility. When prices approach the upper band, the asset may be overbought; near the lower band, it may be oversold.

---

### 6. **On-Balance Volume (OBV)**
- **Formula**:
- 
- OBV = Cumulative (Sign of Price Change x Volume)

- **Explanation**:  
  OBV measures the buying and selling pressure by analyzing volume flow relative to price changes.

---

### 7. **Parabolic SAR (PSAR)**
- **Formula**:  
  PSAR is calculated iteratively using:
  - **Acceleration Factor (AF)**: Starts at 0.02 and increases incrementally by 0.02, up to a maximum (e.g., 0.2).  
  - The formula adjusts based on the highest highs and lowest lows during the trend.

- **Explanation**:  
  PSAR is a trend-following indicator used to identify potential reversals. It provides stop-loss levels during trending markets.

---

### 8. **Short-Term RSI**
- **Formula**:  
  Same as the standard RSI formula but calculated over a shorter period, such as 9 periods.

- **Explanation**:  
  A short-term RSI provides a quicker response to price changes, making it suitable for shorter trading timeframes.

---

### 9. **Bollinger Band Width**
- **Formula**:
-
- Width = Upper Band - Lower Band


- **Explanation**:  
  The Bollinger Band Width indicates market volatility. A wider band suggests higher volatility, while a narrower band suggests lower volatility.

---

### 10. **MACD Signal Line**
- **Formula**:  
  The Signal Line is the EMA of the MACD values, typically over 9 periods.

- **Explanation**:  
  The Signal Line helps smooth the MACD values, making crossover signals easier to identify.
