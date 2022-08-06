# Module_10_Challenge_TimeSeriesAnalysis
## Background

The financial departments of large companies often have to make foreign currency transactions when doing international business, while hedge funds are also interested in anything that will provide an edge in predicting currency movements. Hence, both are always eager to gain a better understanding of the future direction and risk of various currencies. 

In this assignment, the following time series analysis is used to predict future movement of CAD vs Japanese Yen.

1. Time series forecasting
2. Linear regression modelling

# Time Series Forecasting

Question: Do you see any patterns, long-term and/or short? 
Ans: long term : As we can see above plot above the Canadain dollar dropped between the period of 1992 and 2020. 1 CAD was around 120 Yen in 1992 and it decreased to 80 Yen by 2020.
However in short term the CAD has been stable after a volatile drop in 2008; the price being hovering between 70 to 100 Yen/CAD

Question: Do you see any patterns, long-term and/or short?
Ans: Long term : We can see a decline of the CAD/JPY exchange rate from 1 CAD = 101.5 Yen in 2015 to 1 CAD = 78.29 Yen by 2020
Short term: We can see a downtrend between 2015 to 2017 where the CAD/JPY exchange rate decreased from 101.5 to 75.8 Yen
There are short term fluctuations around the trend amd price deviates around the trend line.

Question: What does the model forecast will happen to the Japanese Yen in the near term?
Ans: The model forecasts that the Japanese Yen will gain strength in next 5 days. CAD would be devalued as the price of CAD relative to Yen will decrease.

Question:What does the model forecast will happen to volatility in the near term?
Ans: The model forecasts that the volatility will increase in the near term.

# Conclusions
 
1. Based on your time series analysis, would you buy the yen now?
 Based on time series analysis, the YEN will be stronger compared to CAD, so its a buying opportunity.

2.Is the risk of the yen expected to increase or decrease?
 The the risk will increase in the near future as GARCH model shows high volatility.

3. Based on the model evaluation, would you feel confident in using these models for trading?
 The model can be used with conjunction with other models to come up with a trading decision as p value is insignificant from the model.
 I will be not confindent until i see results from evaluating other models.


# Linear Regression Modelling

# Conclusions

Does this model perform better or worse on out-of-sample data as compared to in-sample data?

The out of sample data has lower RMSE than the in sample data, hence it signals that the out-of-sample data is more concentrated around the line of best fit.
So out of sample data Performed better than in sample data.