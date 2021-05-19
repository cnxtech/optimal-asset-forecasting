# Optimal Asset Forecasting 

The purpose of these notebooks is to test various machine learning predictive models on two sets of asset buckets: Tech stocks and Cryptocurrency. The code uses closing prices pulled from Alpaca API and CoinAPI and converted to CSV files for stocks and crypto assets respectively. The notebooks use the past 15 months of data considering highly volatile market to capture post COVID-19 shock across all models for optimal predictions. As the data in this study is of time series nature, we have used ARIMA, XGBoost, and LSTM models since they are time series friendly.

---

## Technologies

Language: Python3, Pandas 

ARIMA Requirements:


XGBoost Requirements:
numpy, pandas, xgboost, train_test_split from sklearn.model_selection, GridSearchCV, matplotlib.pyplot, plot_importance from xgboost , plot_tree, mean_squared_error from sklearn.metrics, MinMaxScaler from sklearn.preprocessing 

LSTM Requirements:
numpy, pandas, math, hvplot.pandas, Path from pathlib, seed from numpy.random, random from tensorflow, MinMaxScaler from sklearn.preprocessing, Sequential from tensorflow.keras.models and LSTM, Dense, Dropout from tensorflow.keras.layers

External Resources: BTC_data.csv, ETH_data.csv, LTC_data.csv and AMZN_GOOG_MSFT_data.csv

Developed with Google Colab - [Using Google Colab](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index)

---

## Usage

ARIMA:

XGBoost: <br /> 
    Set up: <br /> 
        - Read in closing price data <br /> 
        - Calculate financial indicators and added to the closing price data frame <br /> 
    Usage: <br /> 
        - Specify the train, validate, test split ratio <br /> 
        - Set the parameters <br /> 
        - Option to change the parameters and/or the split ratio to improve performance <br /> 

LSTM: <br /> 
    Set Up: <br /> 
        - Read in closing price data <br /> 
        - Create a dataframe for each set of closing price data <br /> 
        - Create a list of all dataframes to be run in the model <br /> 
    Usage: <br /> 
        - Specify number of units and dropout fraction for the model <br /> 
        - Remove or add layers to model as necessary for performance <br /> 
        - If using window_data function, specify window size <br /> 
        - Select dates to slice the data if necessary <br /> 
        - Specify train/test split ratio <br /> 
        - Option to change model optimizer to improve performance <br /> 
        - Specify number of epochs and batch size to optimize <br /> 

---

## Examples

ARIMA model example:

XGBoost model example:
![xgboost_model](Resources/Images/XGBoost/xgboost_model.png)

LSTM model example:
![lstm_model](Resources/Images/LSTM/lstm_model.png)


---

## Contributors

Drew Disbrow Marnell: dldmarnell@gmail.com <br /> 
Yoko Yamamoto: yyamamo222@gmail.com <br /> 
Apexa Patel: apexa.dhirubhai@gmail.com <br /> 
Matt Epler: epler.matt@gmail.com <br /> 

---

## License

MIT License
Copyright (c) 2021 Drew Disbrow Marnell