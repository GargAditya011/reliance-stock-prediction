# reliance-stock-prediction

A professional Data Science project focused on predicting the stock prices of **Reliance Industries Limited** using statistical modeling. This project implements **ARIMA** and **SARIMAX** to handle trend and seasonality in financial market data.

---

## 🚀 Overview
Predicting stock market movements requires more than just simple regression. This project utilizes advanced time-series analysis to:
* Test for data stationarity using the **Augmented Dickey-Fuller (ADF) Test**.
* Identify optimal parameters $(p, d, q)$ using **ACF** and **PACF** plots.
* Apply **SARIMAX** to capture seasonal patterns and external factors.

## 🛠️ Tech Stack
* **Language:** Python
* **Time-Series Library:** `statsmodels`
* **Data Analysis:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Data Source:** `yfinance`

## 📊 Methodology
1.  **Data Cleaning:** Handling null values and formatting date indices.
2.  **Stationarity:** Applying differencing to make the series stationary.
3.  **Decomposition:** Breaking down RIL stock price into Trend, Seasonality, and Residuals.
4.  **Forecasting:** Training the model on historical data and predicting the next 30 days.



## 📈 Key Visualizations
* **ADF Test Results:** Checking the p-value for stationarity.
* **ACF/PACF Plots:** Determining the Auto-Regressive and Moving Average terms.
* **Actual vs Predicted:** A final plot showing how well the model tracked the Reliance share price.

## ⚙️ Setup & Installation
```bash
    1) Clone the repository
    2) Install dependencies
         -> pip install pandas statsmodels yfinance matplotlib seaborn
Author: Aditya Garg
