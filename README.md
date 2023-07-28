# Time_series_Forecasting
The dataset contains the number of tractors sold for each month from 2003 to 2014. The models  that perform in the project to forecast the sales for next two years are EXPONENTIAL SMOOTHENING MODEL (ETS) $ AUTO REGRESSIVE INTEGRATED MOVING AVERAGE (ARIMA)

Exponential Smoothening Model

1. Make datetime as an index variable
2. Missing values can be filled by using rolling statistics
3. Decompose the series (additive, multiplicative)
4. Find the right values of alpha, beta $ gamma
5. Build the Exponential Smoothening Model (ETS)
6. claculate the errors on the test dataset and forecast the next 2 year sales

SARIMAX model

1. Check the series whether a series is stationary or not (by using Augmented Ducky Fuller (ADF) Test)
2. Certain transformations are done to make series stationary and to find the p,d,q values
3. Find the value of p,d,q using Box-Jenkins methods by plotting auto correlation and partial auto correlation
5. Iterate over these p,d,q,sp,sd,sq,T values to find the best value
6. Built the sarimax model using these values.
7. claculate the errors on the test dataset and forecast the next 2 year sales

