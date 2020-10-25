# Time Series Analysis

In this repository, I have demonstrated time series analysis of below two datasets using ARMA model and performed insample one-day predictions and outsamples forecast.

#### [1. Delhi Climate Forecasting based on data from 2013 - 2017.](https://www.kaggle.com/sumanthvrao/daily-climate-time-series-data)
#### [2. Alcohol Consumption.](https://www.kaggle.com/bulentsiyah/for-simple-exercises-time-series-forecasting)

<br>

### Python Modules: 
``` python
from statsmodels.tsa.stattools import adfuller
from statsmodels.graphics.tsaplots import plot_acf, plot_pacf
from statsmodels.tsa.statespace.sarimax import SARIMAX
from statsmodels.tsa.seasonal import seasonal_decompose
from pmdarima.arima import auto_arima

```

