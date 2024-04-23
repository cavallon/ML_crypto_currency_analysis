# ML_crypto_currency_analysis



## Overview
The purpose of this project is to develop a neural network algorithm to forecast the price of bitcoin over a 10 day period. This is achieved using an LSTM model.

Our initial dataset was from 2010 to 2024, but we decided to cut this down to 2014 - 2024.
Bitcoin was the first cryptocurrency available, establishing an entire new financial market -- its first few years were extremely slow, before exploding in volatility. These first four years of data are unprecedented, and will likely never be seen again -- for any cryptocurrency, since they're representative of a cultural and economic shift in how we interact with currency.

Therefore, the first four years of bitcoin trading are not only irrelevant to training our forecasting algorithm, they would actively pollute the efficacy of it by diluting the more nuanced (but still volatile) data from the following period of an established market. 


# Issues 
Currently, the models evaluation rating is high (~0.95) but the forecast is off by a large amount. 

This is largely due to working with a smaller dataset, as well as our limited timeframe for learning a new model.

# Source

Data obtained from Investing.com


