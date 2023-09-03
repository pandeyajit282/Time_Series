# Time_Series 

Objective :- To build a model for forecasting the gold price.

### Data collection :- 
        Gold rate data from the yfinance (Yahoo finance).

### Preprocessing :- 
        * Selected the daily 'close' price feature as are time series data and dropped rest features.
        2) The daily data is converted into monthly data by using downsampling.
        3) checked for any anomalies.
        4) checked for stationarity of the data using adf test and got output as non stationary.
        5) By using differencing made the data stationary.
        6) Then checked for seasonality and got seasonal data.
        7) Got the model parameters as (1,1,1) (4,1,1,12).

### Model building :-
        1) 
