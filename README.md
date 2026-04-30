# nse-xgboost-trading-agent
AI Agent for NSE green energy stocks (ADANIGREEN, INOXGREEN, JSWEN, SUZLON). Uses XGBoost, LSTM, RF, SVR &amp; GAN for price prediction. VADER/TextBlob sentiment analysis. Autonomous BUY/HOLD/SELL signals. Built with Python 3.12, TensorFlow, yfinance.
# Stock Price Prediction AI Agent

AI Agent for NSE green energy stocks using XGBoost, LSTM, RF, SVR, GAN & sentiment analysis.

## Stocks Covered
ADANIGREEN | INOXGREEN | JSWEN | SUZLON

## Models Used
- XGBoost (Best — MAE ~10.1, R² ~0.91)
- Random Forest, SVR, LSTM
- GAN (TimeGAN-style synthetic data)
- VADER & TextBlob (Sentiment)

## Setup
```bash
pip install -r requirements.txt
jupyter notebook
```

## Features
- Technical indicators: MA, RSI, MACD, Bollinger Bands
- GAN-generated synthetic data
- Sentiment correlation with price returns
- Autonomous BUY / HOLD / SELL agent
