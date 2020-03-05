# Time-Series-Stat
This is short and simple walk through initial steps in evaluating a time series using stat.models in python. The code checks for seasonality and trend, stationarity, sample entropy and finally applies ARIMA.

## Files and Method:
3 different time series provided: Power_consumption, sin_expan and qqq. The first 2 are time series that are rather simple and can be decomposed and analyzed using stat.models. The qqq file is nasdaq etf which is pretty close to a random walk and simple stat models (and most probably deep learning ML models too!) are not capable of tackling the prediction of that.
