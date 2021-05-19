# Optimal Asset Forecasting 

The purpose of this project was to test various machine learning predictive models on two sets of asset buckets: Tech stocks and Crypto Currency. We have used Alpaca API and CoinAPI to pull closing price data for stocks and crypto assets respectively. Our study uses past 15 months of data considering highly volatile market to capture post COVID-19 shock across all models for optimal predictions. As the data in this study is of time series nature, we have used ARIMA, XGBoost, and LSTM since they are time series friendly.

---

## Technologies

Language: Python3, Pandas 

Imports: 

ARIMA:


XGBoost:
numpy, pandas, xgboost, train_test_split from sklearn.model_selection, GridSearchCV, matplotlib.pyplot, plot_importance from xgboost , plot_tree, mean_squared_error from sklearn.metrics, MinMaxScaler from sklearn.preprocessing 

LSTM:
numpy, pandas, hvplot.pandas, Path from pathlib, seed from numpy.random, random from tensorflow, MinMaxScaler from sklearn.preprocessing, Sequential from tensorflow.keras.models and LSTM, Dense, Dropout from tensorflow.keras.layers

External Resources: BTC_data.csv, ETH_data.csv, LTC_data.csv and AMZN_GOOG_MSFT_data.csv

Developed with Google Colab - [Using Google Colab](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index)

---

## Installation



---

## Examples



---

## Contributors

Drew Disbrow Marnell: dldmarnell@gmail.com
Yoko Yamamoto: yyamamo222@gmail.com
Apexa Patel: apexa.dhirubhai@gmail.com
Matt Epler: epler.matt@gmail.com

---

## License

MIT License
Copyright (c) 2021 Drew Disbrow Marnell