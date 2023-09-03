# Time_Series 

Objective :- To build a model for forecasting the gold price.

### Data collection :- 
        Gold rate data from the yfinance (Yahoo finance).

### Preprocessing :- 
        - Selected the daily 'close' price feature as are time series data and dropped rest features.
        - The daily data is converted into monthly data by using downsampling.
        - checked for any anomalies.
        - checked for stationarity of the data using adf test and got output as non stationary.
        - By using differencing made the data stationary.
        - Then checked for seasonality and got seasonal data.
        - Got the model parameters as (1,1,1) (4,1,1,12).

### Model building :-
        - Built two models, Sarima model using the parameter values we got and also using auto_arima function in python,
          then did forecast for 30 data points.   
