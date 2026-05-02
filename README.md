# 📊 Crypto Sentiment vs Trader Performance Analysis
Analysis of relationship between Bitcoin market sentiment (Fear &amp; Greed) and trader performance using Hyperliquid trading data. Includes data cleaning, EDA, and insights on profitability, risk behavior, and trading patterns.

## 🧠 Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using real trading data from Hyperliquid.

The goal is to understand how market emotions influence:
- Trader profitability
- Risk-taking behavior
- Trade size and frequency
- Buy/Sell and Long/Short performance

---

## 📁 Dataset Description

### 1. Trader Dataset (Hyperliquid)
Contains ~211K trade records with:
- Account ID
- Coin (BTC, ETH, etc.)
- Execution Price
- Size (Tokens & USD)
- Side (Buy/Sell)
- Direction (Long/Short)
- Closed PnL
- Fees
- Timestamp

### 2. Sentiment Dataset (Fear & Greed Index)
Contains ~2600 daily records:
- Date
- Sentiment classification (Fear, Greed, etc.)
- Sentiment score (0–100)

#### Links to download Datasets
1.Historical Data - https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing
2.Fear-Greed Index Data - https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

---

## 🎯 Objectives

- Analyze how sentiment affects trading performance
- Identify profitability trends across market emotions
- Study risk behavior during Fear vs Greed phases
- Compare Buy/Sell and Long/Short performance
- Find top performing coins

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Key Analysis Performed

### 1. Sentiment vs Profitability
- Average Closed PnL by sentiment

### 2. Trade Activity
- Number of trades during different sentiment phases

### 3. Risk Behavior
- Trade size variations across sentiment

### 4. Strategy Comparison
- Buy vs Sell performance
- Long vs Short performance

### 5. Market Impact
- Relationship between sentiment score and profitability

### 6. Asset Performance
- Most profitable coins

---

## 📈 Key Insights

- Traders were most profitable during Extreme Greed sentiment.
- Trade size increased during Fear periods.
- Trader profitability varies significantly with market sentiment
- Extreme Greed periods show higher risk-taking behavior
- Buy/Sell effectiveness changes based on sentiment conditions
- Certain coins consistently outperform others in profitability
- Trading activity increases during optimistic market conditions

---

## 📌 Project Structure

crypto-sentiment-trading-analysis/
│
├── data/
│   ├── trader_data.csv
│   ├── sentiment_data.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_analysis.ipynb
│   ├── 03_insights_visualization.ipynb
│
├── visuals/
│   ├── pnl_by_sentiment.png
│   ├── trade_count.png
│   ├── buy_sell_analysis.png
│
├── src/
│   ├── data_preprocessing.py
│   ├── analysis.py
│   ├── visualization.py
│
├── requirements.txt
├── README.md
└── .gitignore



