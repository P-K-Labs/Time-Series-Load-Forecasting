# Time-Series-Load-Forecasting
Developed and compared different time series models for effectively capture load trend, seasonality's and other cyclical variations to generate accurate forecasts for 1 year

The following models were developed:-
- Linear Model with Hourly, Weekly and Monthly interaction terms
- Linear Model with 48 lags
- XGBoost with 48 lags
- XGBoost with Hourly, Weekly and Monthly interaction terms
- KNN with Seasonality and transformed target variable without exogenous variables
- LightGBM with Seasonality, trend and transformed target variable with exogenous variables (Best Model)
- Ensemble Model of LightGBM and Adaboost
