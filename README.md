# Energy Consumption Analysis

## Objective
I analyzed energy consumption data from 2010 to 2018 and made a forecast using Facebook Prophet. 

## Process
I start by cleaning the data and deal with missing values. I then look at the overall data to get a sense of its structure, trends and anomalies. I also do a bit of feature engineering to find novel connections and detect seasonality. Afterwards, I decompose the data to look at its seasonality, trend and residuals individually. I perform the Dickey-Fuller test to check if the data is stationary. I also use autocorrelation/partialcorrelation to see significant lag values I can use for better understanding and as parameters to models like ARIMA. I create a simple base model for a benchmark using persistence algorithm. I do a general overview of different appraoches I can take before using Facebook Prophet.
