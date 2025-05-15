# Time Series Forecasting

## Project Overview

This project focuses on building and evaluating a time series model to forecast a target metric over time. The dataset simulates business-relevant temporal patterns, and the objective was to analyze trends, seasonal behavior, and overall stationarity before selecting an appropriate forecasting model.

## Objectives

- Explore and visualize time-dependent trends and seasonality
- Apply statistical tests to assess stationarity
- Build forecasting models using SARIMA and related techniques
- Evaluate performance using time-aware validation

## Tools & Technologies

- Python  
- pandas, NumPy  
- statsmodels, pmdarima  
- matplotlib, seaborn  
- Jupyter Notebook  

## Methodology

1. Conducted exploratory data analysis with rolling averages and seasonal decomposition  
2. Tested for stationarity using the Augmented Dickey-Fuller (ADF) test  
3. Differenced the series and plotted ACF/PACF to identify autoregressive and moving average parameters  
4. Trained a SARIMA model with optimized parameters  
5. Evaluated results using Mean Absolute Error (MAE) and visual inspection of forecast accuracy

## Key Results

- Seasonal decomposition revealed strong periodicity in the data  
- Differencing and parameter tuning were required to stabilize the series  
- The final SARIMA model provided accurate short-term forecasts with minimal error and no significant autocorrelation in residuals

## Limitations & Future Work

- Accuracy may be sensitive to sudden shocks or non-recurring events  
- Additional exogenous variables (SARIMAX) could improve predictive power  
- Next steps may include automating retraining and deployment as a forecasting service


