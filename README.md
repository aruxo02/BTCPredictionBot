# BTC Prediction Bot 🤖📈

[![Join Telegram Channel](https://img.shields.io/badge/Telegram-Join-blue?logo=telegram)](https://t.me/BTCIAPREDICTION)

Welcome to the **BTC Prediction Bot** repository! This bot ingests and processes a comprehensive set of data to forecast Bitcoin (BTC/USD) prices at multiple horizons.

---

## 🔍 Accuracy

- **1 hour horizon**: 72% classification accuracy
- **2 hours horizon**: 68% classification accuracy
- **4 hours horizon**: 65% classification accuracy

---

## 📈 Key Data Domains

Every 30 minutes, the pipeline gathers 100+ features from various domains:

### 🔗 On‑chain Data
Metrics describing blockchain activity and BTC network health (dominance, market cap, transaction counts, hashrate, difficulty).

### 🌍 Macroeconomic & External Factors
Global economic indicators (inflation rates, money supply, bond yields, equity indices, commodities, VIX, unemployment).

### 🧮 Technical Indicators
Classical technical analysis metrics (moving averages, MACD, Bollinger Bands, ATR, momentum oscillators, volatility measures).

### 🤝 Social & News Sentiment
Sentiment scores and positive/negative/neutral counts from platforms like Reddit, Twitter, and various news categories (general, macro, hacking, mining, adoption).

### 💹 Derivatives & ETF Flows
Futures prices and funding rates, plus ETF inflow/outflow volumes and detected outflows for major BTC ETFs.

### 📊 Additional Statistics
Various calculated ratios, distribution buckets, liquidation data, exchange spreads, miner revenue, and many more advanced computation fields (too many to list here).

*(Full schema available in `data_schema.md`)*

---

[![Join Telegram Channel](https://img.shields.io/badge/Telegram-Join-blue?logo=telegram)](https://t.me/BTCIAPREDICTION)

*Data pipeline runs every 30 minutes and retrains models daily after 02:00 UTC.*

Feel free to explore, contribute, and deploy your own instance!

