## INTRODUCTION

* A time series is a sequence or series of numerical data points fixed at certain chronological time order. In most cases, a time series is a sequence taken at fixed interval points in time. This allows us to accurately predict or forecast the necessities.

* Time series uses line charts to show us seasonal patterns, trends, and relation to external factors. It uses time series values for forecasting and this is called extrapolation.

* Time series are used in most of the real-life cases such as weather reports, earthquake prediction, astronomy, mathematical finance, and largely in any field of applied science and engineering. It gives us deeper insights into our field of work and forecasting helps an individual in increasing efficiency of output.

* Time series is an important part of machine learning. It figures out a seasonal pattern or trend in the observed time-series data and uses it for future predictions or forecasting. Forecasting involves taking models rich in historical data and using them to predict future observations.

![image](https://user-images.githubusercontent.com/68374336/185292903-de103c28-1e4e-4892-a5c4-0dab2892115a.png)



#### There are two main types of forecasting methods, namely, Qualitative Forecasting and Quantitative Forecasting.

In Qualitative Forecasting, the forecasting decisions are dependent upon expert opinions. There is no data available to study the patterns in order to make forecasting decisions. Since human decision making is involved, there is a chance of bias.

In Quantitative Forecasting, data with patterns is available and these patterns can be aptly captured with the help of computers. Hence human decision making is not involved, due to which there is no chance of human bias.


![image](https://user-images.githubusercontent.com/68374336/185292932-6743cd75-47a1-4f17-b186-af1afe190ecc.png)



Level : Any time series will have a base line. To this base line we add different components to form a complete time series. This base line is known as level.

Trend : It defines whether, over a period, time series increases or decreases. That is, it has an upward (increasing) trend or downward (decreasing) trend. For eg. the above time series has an increasing trend.

Seasonality : It defines a pattern that repeats over a period. This pattern which repeats periodically is called as seasonality. In the above graph, we can clearly see the seasonality component present.

Cyclicity : Cyclicity is also a pattern in the time series data but it repeats aperiodically, meaning it doesn’t repeat after fixed intervals.

Noise : After we extract level, trend, seasonality/cyclicity, what is left is noise. Noise is a completely random fluctuation in the data.

* Autoregression Model (AR)- AR is a time series model that uses observations from previous time steps as input to a regression equation to predict the value at the next time step.

![image](https://user-images.githubusercontent.com/68374336/185293889-abf1c2d5-50a2-4be7-b960-c7a1562b09fe.png)



* Moving Average Model (MA)- The residual errors from forecasts in a time series provide another source of information that can be modeled. The Residual errors form a time series. An autoregression model of this structure can be used to foresee the forecast error, which in turn can be used to correct forecasts.

![image](https://user-images.githubusercontent.com/68374336/185293915-f6905a88-1a5c-4c04-bcdb-89a496b1b130.png)


* Auto regression moving average method (ARMA)- It’s a combination of AR and MA models.

![image](https://user-images.githubusercontent.com/68374336/185293975-a90b8f3f-c3f9-43a9-8890-82f9f01cb478.png)


* Auto regressive integrated moving average (ARIMA)- It is same as ARMA model, just has an additional integrated differencing component in it.


![image](https://user-images.githubusercontent.com/68374336/185294031-749aeb3c-d5bf-4ef7-b26b-f5f5525c0369.png)


* Seasonal auto regressive integrated moving average (SARIMA)- SARIMA is same as ARIMA, it just has an additional component of seasonality in it.

![image](https://user-images.githubusercontent.com/68374336/185294110-c2fbfd28-6aca-48ff-b9de-58e3129f73d4.png)


### NOTE- After implementing all the forecasting models, we calculate the RMSE and MAPE for all the methods.








