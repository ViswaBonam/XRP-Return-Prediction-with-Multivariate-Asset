# XRP Returns Analysis with Multivariate Financial Assets 📊

This project investigates the potential predictive relationship between **XRP** (Ripple) returns and other macro/market indicators. The analysis uses historical data from traditional financial assets to explore how these indicators might influence XRP.

---

## 📌 Objective

To analyze whether macroeconomic and financial market indices (e.g., NASDAQ, Dollar Index, Emerging Markets ETF) exhibit any predictive power over XRP cryptocurrency returns.

---

## 🔍 Assets Analyzed

- **XRP-USD**: Primary asset under investigation (Ripple cryptocurrency)
- **^IXIC (NASDAQ Composite)**: Represents tech sector performance
- **^CMC200 (Crypto Market Cap Index)**: Reflects overall crypto volatility
- **DX-Y.NYB (Dollar Index - DXY)**: Strength of the US Dollar
- **EEM (Emerging Markets ETF)**: Indicates global investor sentiment and risk appetite

---

## 🧠 Hypothesis

> Multivariate financial indicators can act as leading signals to XRP price action due to macroeconomic correlation and cross-asset investor sentiment.

---

## 📊 Methodology

- Historical data pulled from **Yahoo Finance** (`yfinance`)
- Daily log returns calculated for all assets
- Visual and statistical exploration of:
  - Rolling correlations
  - Pairwise relationships
  - Lead-lag trends

---

## 📁 Files

- `XRP_Returns_Analysis_Multivariate_Assets.ipynb`: Main notebook for analysis

---

## 🧰 Libraries Used

- pandas
- numpy
- matplotlib
- yfinance
- xgboost
- shap
- sqlite3
- sklearn (via `roc_auc_score`)
- functools (`reduce`)

---
