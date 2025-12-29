  
#  Technical Analysis Using Python (Finance)

##  Project Overview
This project implements an **end-to-end algorithmic trading strategy** using Python by combining **momentum** and **volume-based indicators** to identify high-probability entry and exit points in the stock market.

The strategy is **backtested on 9 years of historical Apple Inc. (AAPL) data** and demonstrates strong **risk-adjusted performance**, achieving a **Sharpe Ratio of 11.18**.

---

##  Indicators Used
1. **Relative Strength Index (RSI)**
2. **On-Balance Volume (OBV)**

---

##  Strategy Logic
The trading strategy uses confirmation from both indicators to generate signals:

### Relative Strength Index (RSI)
- Measures price momentum  
- **Buy Signal:** RSI < 35 (oversold condition)  
- **Sell Signal:** RSI > 85 (overbought condition)  

### On-Balance Volume (OBV)
- Relates price movement to volume flow  
- **Buy Signal:** OBV crosses above its 50-day Exponential Moving Average (EMA)  
- **Sell Signal:** OBV crosses below its 50-day EMA  

Trades are executed **only when both indicators align**, reducing noise and false signals.

---

##  Implementation Details
- **Language:** Python  
- **Libraries Used:** pandas, numpy, matplotlib  
- **Data Source:** yfinance (Yahoo Finance API)  
- **Timeframe:** Daily price data  
- **Backtesting Period:** ~9 years  

---

##  Performance Metrics
- **Number of trades executed:** 21  
- **Win rate:** 85.71%  
- **Sharpe Ratio:** 11.18  
- **Maximum Drawdown:** -16.26%  
- **Total Strategy Return:** 927.96%  
- **Profit-making trades:** 18  
- **Loss-making trades:** 3  

---


## 👤 Author
**Omprakash Balara**  
B.Tech Mechanical Engineering, IIT Roorkee
