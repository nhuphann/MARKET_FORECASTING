This project analyzes the daily stock returns of NVIDIA Corporation (NVDA) from 2016 to 2024 using various time series forecasting models in both R and Python. The goal is to evaluate and compare these models to determine the most reliable forecasting approach for future returns.

## Objective

Evaluate multiple time-series forecasting models to determine which method yields the most accurate predictions for NVIDIA stock returns, using diagnostic plots and forecasting error metrics.

---

## 📊 Study Summary

- **Data Source**: Yahoo Finance (2016–2024)
- **Target Variable**: Daily NVDA stock returns
- **Forecasting Horizon**: Short- to medium-term prediction
- **Languages Used**: R and Python
- **Goal**: Identify the most accurate and stable model for return forecasting

---

## 🔍 Methods

- Stationarity testing using **Augmented Dickey-Fuller test**
- Forecasting models applied:
  - ARIMA
  - ETS (Exponential Smoothing)
  - Holt-Winters
  - NNAR (Neural Networks for Time Series)
  - Prophet (Facebook)
- Forecast combination using **averaged model predictions**
- Evaluation metrics: **RMSE**, **MAE**, **MAPE**, **MPE**
- Residual analysis for autocorrelation and normality

---

## 📈 Key Findings

- **ETS** performed best, with the lowest RMSE and MAE
- **Holt-Winters** was the weakest performer across metrics
- Forecast averaging produced **stable but not superior** results
- Residuals showed remaining **autocorrelation**, indicating model limitations

---

## 🧪 Tools Used

- **R**: `forecast`, `prophet`, `nnetar`, `ggplot2`, `quantmod`
- **Python**: `pandas`, `statsmodels`, `fbprophet`
- **Version Control**: Git and GitHub
- **Data Source**: Yahoo Finance
