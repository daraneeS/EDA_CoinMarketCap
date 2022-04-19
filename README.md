# Data Collection & Preprocessing: CoinMarketCap

## Overview

This project shows process of getting data from compliated API calls. 
Some **JSON** files are complicated because of **nested dictionaries** 
or **a list of nested dictionary**
This project is able to get the **Inactive/Active Coins** listed on **CoinMarketCap API** and create **Pandas DataFrames**

![png](images/btc_close_line.png)


## Data Source and Preparation

**Three CoinMarketCap API endpoints**
* **Category Endpoint**
* **Categories Endpoint**
* **Listing Latest Endpoint**


## Visualization

![png](images/btc_close_box.png)

![png](images/btc_vol_line.png)

![png](images/btc_vol_box.png)

![png](images/btc_trds_line.png)

![png](images/btc_trds_box.png)


## Possible Application

* Help inform retail investors/users possible close price, ruturn , trend of Bitcoin and other cryptocurrency
* The model can be developed to live prediction and with shorter timeframe, 4 hours, 1 hours as example
* The model can be improved, modified and used with other cryptocurrency or stocks

## Futher Improvement
* Using other machine learning models to compare and improve accuracy of the prediction, such as XGBoost, Random Forest, Deep Learning/LSTM etc.
* Adding more features such as VWAP, RSI, etc.
* Shorter timeframe such as 4 hours, 1 hours, 30 minutes etc.
