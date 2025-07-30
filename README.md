# 📈 Stock Market Data Analysis (S&P 500 Companies)

This project performs an exploratory data analysis (EDA) on the historical stock price data of companies listed in the S&P 500 index using Python, Pandas, NumPy, and Matplotlib. It focuses on understanding trends, volatility, and comparing stock performance across multiple companies — without using machine learning.

---

## 📂 Dataset

- **Source**: [S&P 500 Stock Data on Kaggle](https://www.kaggle.com/datasets/camnugent/sandp500)
- **File used**: `all_stocks_5yr.csv`
- Contains daily open, close, high, low, and volume data for 500 companies from 2013 to 2018.

---

## 🎯 Objectives

- Load and clean stock market data
- Analyze closing prices over time for selected companies
- Calculate and visualize:
  - Daily returns
  - Moving averages (50-day, 200-day)
  - Volatility (30-day rolling standard deviation)
- Compare stock performance between companies like Apple, Amazon, and Google

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Key Insights

- Amazon shows consistent upward growth from 2013 to 2018.
- Apple stock has periods of volatility that are smoothed using moving averages.
- Google, Apple, and Amazon all show positive trends but vary in volatility and daily returns.
