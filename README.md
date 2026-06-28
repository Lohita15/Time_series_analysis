# 📈 Time Series Analysis Capstone Project

## Overview

This repository contains my submission for the **Time Series Analysis 2026 Capstone Project** conducted by the **Consulting & Analytics Club, IIT Guwahati**.

The project focuses on forecasting stock prices using classical time series models, constructing an optimized investment portfolio, and validating predictions through live virtual trading on the StockGro platform.

🏆 **Achievement:** Awarded the **Certificate of Excellence** and ranked in the **Top 10th Percentile** of participants.

---

## Project Objectives

- Forecast short-term stock prices using historical NSE data.
- Compare multiple time series forecasting models.
- Analyze stock volatility and sector diversification.
- Construct a risk-aware investment portfolio.
- Execute a ₹10,00,000 virtual portfolio on StockGro.
- Compare predicted market movements with actual outcomes.

---

## Dataset

- **Source:** Yahoo Finance (yfinance)
- **Time Period:** January 2021 – December 2025
- **Frequency:** Daily Closing Prices

### Stocks Selected

| Stock | Sector |
|--------|---------|
| HDFC Bank | Banking |
| Infosys | IT |
| ITC | FMCG |
| Sun Pharma | Pharma |
| Maruti Suzuki | Automobile |

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Prophet
- yfinance
- Power BI
- StockGro

---

## Workflow

### 1. Data Collection

- Downloaded historical NSE stock data using yfinance.
- Cleaned missing values using forward-fill.

---

### 2. Data Preprocessing

- Exploratory Data Analysis
- Stationarity testing (ADF Test)
- First-order differencing
- Train/Test split

---

### 3. Forecasting Models

Implemented and compared:

- ARIMA
- Facebook Prophet
- Exponential Smoothing (ETS)

Performance was evaluated using:

- Mean Absolute Percentage Error (MAPE)
- Directional Accuracy

---

### 4. Volatility Analysis

Calculated:

- Log Returns
- Annualized Volatility
- Correlation Matrix

Used inverse-volatility weighting for portfolio optimization.

---

### 5. Portfolio Construction

Portfolio allocation was based on:

- Forecasted returns
- Inverse volatility weighting

Virtual capital:

**₹10,00,000**

Stocks Executed:

- ITC
- Infosys
- Maruti Suzuki

---

### 6. Live Virtual Trading

The portfolio was deployed on **StockGro** to compare model predictions against live market performance.

Portfolio Summary

| Metric | Value |
|---------|-------|
| Invested Amount | ₹7,14,366.77 |
| Final Portfolio Value | ₹7,13,561.50 |
| Overall Return | -0.08% |

---

## Power BI Dashboard

The project includes an interactive Power BI dashboard featuring:

- Portfolio allocation
- Forecast comparison
- Stock performance
- Sector analysis
- Correlation heatmap
- Portfolio returns

---

## Repository Structure

```
├── data/
├── notebooks/
│   └── TSA_Capstone.ipynb
├── dashboard/
│   └── TSA_Dashboard.pbix
├── report/
│   └── TSA_Capstone_Report.pdf
├── images/
├── requirements.txt
└── README.md
```

---

## Key Learnings

- Time Series Forecasting
- Financial Data Analysis
- Portfolio Optimization
- Volatility Analysis
- Model Evaluation
- Data Visualization
- Business Intelligence

---

## Future Improvements

- LSTM & GRU Models
- Transformer-based Forecasting
- GARCH Volatility Modeling
- Hyperparameter Optimization
- Automated Trading Signals
- Streamlit Web Application

---

## Author

**Lohitha Reddy**

LinkedIn: *www.linkedin.com/in/lohitareddy15*

GitHub: *https://github.com/Lohita15*

---

## Acknowledgements

This project was completed as part of the **Time Series Analysis 2026** program organized by the **Consulting & Analytics Club, IIT Guwahati**, in collaboration with **StockGro**.
