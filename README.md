# Technical_Analysis_using_Python_Finance

## Project Overview
This project implements an end-to-end algorithmic trading strategy using Python. It combines momentum and volume indicators to identify high-probability entry and exit points in the stock market. The strategy was backtested on 9 years of historical Apple Inc. (AAPL) data, achieving a significant Sharpe Ratio of 11.18.v

## Indicators Used
1. Relative Strength Index (RSI)
2. On-Balance Volume (OBV)

## Strategy Logic
The strategy relies on the synergy between two primary technical indicators:
1. Relative Strength Index (RSI): Measures price momentum.
     Buy Signal: RSI < 35 (Oversold conditions).
     Sell Signal: RSI > 85 (Overbought conditions).
2. On-Balance-Volume (OBV): Relates price change to volume flow.
     Buy Signal: OBV crosses above its 50-day Exponential Moving Average (EMA).
     Sell Signal: OBV crosses below its 50-day EMA.


## Implementation Details
  Language: Python
  Libraries used: pandas , numpy, matplotlib 
  Data Source: yfinance (Yahoo Finance API)



## Performance Metrics

  Number of trades executed: 21
  Win rate: 85.71%
  Sharpe Ratio: 11.18
  Maximum Drawdown: -16.26%
  Strategy Return: 927.96%
  Profit-making trades: 18
  Loss-making trades: 3
  
