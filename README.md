# NVIDIA Options Trade Predictor

## Objective
Use stock data, technical indicators, and financial news (Trump, Powell, VIX, Fed) to predict directional movement of NVDA and recommend profitable call/put option trades.

## Target Outputs
- Predicted movement: Bullish or Bearish
- Confidence score
- Suggested option trade (strike, expiry)

## Features Used
- Historical NVDA price + volume
- Technical indicators (SMA, RSI, MACD)
- News sentiment (FinBERT)
- VIX levels
- Powell & Trump news
- Earnings call analysis

## Time Horizon
Model uses 7-30 days of data to predict the next 1-5 day movement.
