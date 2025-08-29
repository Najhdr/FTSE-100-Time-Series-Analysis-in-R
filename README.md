FTSE 100 Time Series Forecasting
This project investigates the FTSE 100 index by analyzing its historical trend, comparing it with a linear regression fit, forecasting future values using Prophet, and decomposing the series to better understand its components.
The aim is to build an understanding of how the FTSE 100 behaves over time, identify long-term patterns, and generate a two-year forecast.

1. Dataset
- Index: FTSE 100 (UK stock market index)
- Source: Yahoo Finance
- Frequency: Monthly closing prices
- Period Covered: January 2010 – December 2019

2. Methodology
   
i. Trend Analysis: Visualized the FTSE 100 historical trend over 10 years.
  
ii. Linear Regression Comparison:
- Fitted a linear regression model to compare its predictive power with actual index values.
- Assessed limitations of linear regression in capturing financial time series dynamics.
  
iii. Forecasting with Prophet:
- Implemented Facebook Prophet to predict the next 2 years of FTSE 100 values.
- Captured both trend and seasonal components.
  
iv. Time Series Decomposition:
- Decomposed the index into trend, seasonality, and residuals.
- Highlighted underlying patterns and volatility in the series.

3. Result

i. Linear regression captured the overall upward trend but failed to adapt to fluctuations.

ii. Prophet produced more realistic 2-year forecasts with confidence intervals, accounting for both trend and seasonal behavior.

iii. Decomposition revealed:
- Trend: Gradual growth over the period.
- Seasonality: Small recurring fluctuations.
- Residuals: Unpredictable shocks, reflecting market volatility.
  
(Insert figures here: historical trend plot, regression comparison, Prophet forecast, decomposition charts.)

