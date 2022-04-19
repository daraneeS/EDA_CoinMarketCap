# Data Collection & Preprocessing: CoinMarketCap

## Overview

This project shows process of getting data from compliated API calls. 
Some **JSON** files are complicated because of **nested dictionaries** 
or **a list of nested dictionary**
This project is able to get the **Inactive/Active Coins** listed on **CoinMarketCap API** and create **Pandas DataFrames**

![png](images/btc_close_line.png)


## Data Source and Preparation

**Three CoinMarketCap API endpoints**
* *Category Endpoint*
* *Categories Endpoint*
* *Listing Latest Endpoint*


## Visualization

![png](images/num_coins_2013_2022.png)

![png](images/num_coins_2013_2022_pie.png)

![png](images/platform_most_coins_pie.png)

![png](images/cat_most_coins.png)

![png](images/cat_dead_coins_bar.png)

![png](images/cat_dead_coins_bar.png)

![png](images/cat_live_bar.png)

## Possible Application

* Help inform retail investors/users possible close price, ruturn , trend of Bitcoin and other cryptocurrency
* The model can be developed to live prediction and with shorter timeframe, 4 hours, 1 hours as example
* The model can be improved, modified and used with other cryptocurrency or stocks

## Futher Improvement
* Using other machine learning models to compare and improve accuracy of the prediction, such as XGBoost, Random Forest, Deep Learning/LSTM etc.
* Adding more features such as VWAP, RSI, etc.
* Shorter timeframe such as 4 hours, 1 hours, 30 minutes etc.
