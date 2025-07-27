# Sales Forecasting: Prophet vs SARIMA

## Overview
This project focuses on **time series forecasting** of retail sales data using two approaches:
- **Prophet**: A model developed by Facebook that handles trend, seasonality, and holidays effectively.
- **SARIMA**: A classical statistical model (Seasonal Autoregressive Integrated Moving Average) often used for seasonal time series data.

The goal of the project is to:
- Clean and preprocess real-world retail sales data.
- Perform **Exploratory Data Analysis (EDA)** to understand trends, seasonality, and outliers.
- Train forecasting models (**Prophet** and **SARIMA**) and compare their performance.
- Visualize forecasts, confidence intervals, and model accuracy metrics (MAE and RMSE).

---

## Dataset
The dataset used in this project is from the **[Store Sales Time Series Forecasting Competition on Kaggle](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)**.

**Note:**  
The dataset is too large to be stored directly in this repository.  
You can download it directly from Kaggle:
- [Download Dataset](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)

After downloading, place the `train.csv` file in the `data/` folder of the project:
