# Lahore Weather Analysis and Forecasting

This project focuses on analyzing and forecasting weather patterns in Lahore using historical precipitation data. The application uses time series models such as ARIMA, SARIMA, and Auto ARIMA to identify trends, visualize weather patterns, and predict future precipitation levels.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Dataset](#dataset)
5. [Data Preprocessing](#data-preprocessing)
6. [Models Implemented](#models-implemented)
7. [Results and Insights](#results-and-insights)
---

## Introduction

The project leverages advanced time series analysis to provide insights into rainfall patterns in Lahore during July and August. Using historical data, the application forecasts monthly precipitation, helping in understanding climatic trends and preparing for monsoon seasons.

---

## Features

- **Data Analysis:**
  - Monthly and yearly precipitation trends.
  - Maximum daily precipitation during July and August.
  - Number of rainy days per month and year.

- **Time Series Modeling:**
  - ARIMA, SARIMA, and Auto ARIMA for forecasting precipitation.

- **Visualizations:**
  - Bar charts for rainy days and total precipitation.
  - Line plots for observed vs. forecasted precipitation.

- **Performance Metrics:**
  - Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

---

## Technologies Used

- **Programming Language:** Python
- **Libraries:**
  - `pandas`, `numpy` for data manipulation.
  - `matplotlib`, `seaborn` for visualization.
  - `statsmodels`, `pmdarima` for time series analysis.
  - `scikit-learn` for evaluation metrics.

---

## Dataset

- **Source:** Historical weather data for Lahore.
- **Timeframe:** July and August (2019-2023).
- **Features:**
  - Date and time.
  - Precipitation values.

---

## Data Preprocessing

1. Combined date and time columns into a single datetime format.
2. Filtered data for July and August.
3. Aggregated hourly data into monthly and daily summaries.
4. Checked and handled missing or inconsistent data.

---

## Models Implemented

### ARIMA (Autoregressive Integrated Moving Average)
- Non-seasonal time series model for forecasting.

### SARIMA (Seasonal ARIMA)
- Seasonal time series model incorporating yearly trends.

### Auto ARIMA
- Automated model selection for optimal ARIMA configuration.

---

## Results and Insights

- **Performance Metrics:**
  - ARIMA achieved RMSE of X mm.
  - SARIMA achieved RMSE of Y mm.
  - Auto ARIMA achieved RMSE of Z mm.

- **Key Insights:**
  - Rainfall patterns show a seasonal increase during July and August.
  - Prediction models effectively capture precipitation trends for short-term forecasting.

---
