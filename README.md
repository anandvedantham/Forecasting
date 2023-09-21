# Forecasting
Forecasting is a process used to make predictions or estimates about future events, trends, or outcomes based on historical data and analysis. It plays a crucial role in various fields, including economics, finance, weather, business, and more. The goal of forecasting is to reduce uncertainty and help individuals, organizations, and governments make informed decisions.

Forecasting typically begins with the collection and analysis of historical data related to the phenomenon being forecasted. This data can include numerical information, such as sales figures, stock prices, or weather measurements, as well as qualitative data like customer surveys or expert opinions. Many forecasting methods are designed for time series data, where observations are collected over time at regular intervals. Time series analysis involves identifying patterns, trends, and seasonality in the data. 

 Advanced machine learning and artificial intelligence techniques, such as neural networks and deep learning, can be used for forecasting when dealing with complex and large datasets.

 ## Implementation
 
- Importing the required Libraries and reading the dataset
- Performing EDA on the data
- Feature Engineer
- Visualizations
- Moving Average
  - Time series decomposition plot
  - Autocorrelation Plot (ACF)
  - Partial Autocorrelation Plot (PACF)
- Data Preprocessing
- Splitting the data into Train and Test data
- Choosing the Evaluation Metrics - RMSE & MAPE
- Building the Models
  - Linear Model, Exponential Model, Quadratic Model
  - Exponential Smoothing
    - Simple Exponential, Holt Method, Holts Winter Exponential Smoothing
  - Seasonalities
    - Additive, Additive with quadratic trend, Multiplicative, Multiplicative Additive Seasonality
  - ARIMA Model
- Conclusion
  - Comparing all the created models
  - Finalized Model

## Packages Used

- pandas, numpy
- matplotlib.pyplot, seaborn
- warnings
- from pandas import Grouper
- from pandas.plotting import lag_plot
- from statsmodels.graphics.tsaplots import plot_acf
- from statsmodels.graphics.tsaplots import plot_pacf
- import statsmodels.formula.api as smf
- from statsmodels.tsa.seasonal import seasonal_decompose
- from statsmodels.tsa.holtwinters import SimpleExpSmoothing
- from statsmodels.tsa.holtwinters import Holt
- from statsmodels.tsa.holtwinters import ExponentialSmoothing
- from sklearn.metrics import mean_squared_error
- from statsmodels.tsa.arima.model import ARIMA
- from statsmodels.tsa.stattools import adfuller
