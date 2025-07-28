# Sales Forecasting Using SARIMAX

This project applies SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors) to forecast future sales based on historical time series data.

## 📊 Overview

Time series analysis is a powerful tool for forecasting, and SARIMAX extends ARIMA by handling seasonality and external factors. This project uses historical sales data to build a predictive model.

## 🛠️ Techniques Used

- Time series decomposition
- Stationarity testing (ADF Test)
- Seasonal differencing
- SARIMAX modeling (using `statsmodels`)
- Forecast evaluation (MAE, RMSE)

## 🔍 Results

The forecast indicates continued seasonal behavior and an upward trend in transactions. Confidence intervals widen into the future, reflecting increasing uncertainty in long-term predictions.

![forecast-plot](path/to/your/forecast-plot.png)

## 📦 Requirements

- pandas
- numpy
- matplotlib
- statsmodels
- seaborn (optional)

Install with:

```bash
pip install -r requirements.txt


