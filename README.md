# BTC vs S&P 500 Portfolio Analysis

© Begum Celebi, December 2025

## Overview
This repository contains a Python-based analysis of Bitcoin (BTC) and S&P 500 returns over the past five years. 
The analysis incorporates the 10-Year US Treasury yield as a proxy for the risk-free rate. 
The goal is to explore correlation dynamics, risk, and portfolio allocation using Modern Portfolio Theory (MPT).

---

## Features

- Descriptive statistics of daily returns
- Cumulative returns comparison
- 30-day rolling correlation (BTC vs S&P 500, BTC vs 10Y yield)
- 30-day rolling volatility comparison
- Histogram of daily returns
- Annual average correlation table
- Optimal portfolio allocation (BTC & S&P 500) using MPT

---

## Data Source & Preparation

All data was collected manually from [Investing.com](https://www.investing.com/) and saved as CSV files. 
The datasets were then cleaned to ensure consistent date formats and numeric return values suitable for analysis.

- `btc_historical-data .csv` — daily BTC price changes
- `spy_historical_data .csv` — daily S&P 500 price changes
- `us_10yr_yield .csv` — daily 10-Year US Treasury yields

> Note: The data covers at least the past 5 years with daily frequency. All columns were cleaned to remove symbols and converted to numeric values for analysis.

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/btc_sp500_portfolio_analysis.git
