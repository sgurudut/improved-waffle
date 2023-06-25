# improved-waffle # time-series # model-comparision # arima # sarima

Time Series Analysis: Comparing ARIMA and SARIMA Models.

The goal was to compare Autoregressive integrated moving average (ARIMA) and Seasonal Autoregressive integrated moving average (SARIMA) models. 

- Gathered the data from Kaggle (https://www.kaggle.com/datasets/bilalwaseer/google-stocks-complete)
- Performed tests (ADF and KPSS) to check if the series was stationary.
- Perfomed differncing to make the series stationary
- Plotted relevant autocorrelation plots (ACF and PACF)
- Forecasted values for the valid data and comared Arima and Sarima models

Results

For this dataset, RMSLE was used to comapre the models and it was found that Arima model performed better than Sarima model by 85%.

Next Steps:
- Perform hyperparameter tuning
- Forecast using prophet
- Forecast using deep learning models
