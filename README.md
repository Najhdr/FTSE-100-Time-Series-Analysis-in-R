# FTSE 100 Time Series Forecasting

This project analyzes and forecasts the FTSE 100 index to understand its historical behavior, identify long-term patterns, and generate future predictions. The workflow combines exploratory analysis, statistical modeling, and machine learning techniques to compare simple and advanced forecasting approaches.

---

## Dataset
- **Index**: FTSE 100 (UK stock market index)  
- **Source**: Yahoo Finance  
- **Frequency**: Monthly closing prices  
- **Period Covered**: January 2010 – December 2019  

---

## Methodology

1. **Trend Analysis**  
   - Visualized the FTSE 100 over a 10-year period to highlight overall growth and volatility.  

2. **Linear Regression Benchmark**  
   - Fitted a linear regression line against historical data.  
   - Compared predictions to actual values to show the limitations of linear models in capturing financial time series dynamics.  

3. **Forecasting with Prophet**  
   - Implemented **Facebook Prophet** to predict the next 2 years of FTSE 100 values.  
   - Captured both **trend** and **seasonality** with confidence intervals.  

4. **Time Series Decomposition**  
   - Decomposed the series into **trend, seasonality, and residuals**.  
   - Provided insights into underlying growth, recurring patterns, and unpredictable shocks.  

---

## Results

- **Linear Regression**  
  - Captured the long-term upward trend but failed to reflect short-term fluctuations.  

- **Prophet Forecast**  
  - Generated realistic 2-year predictions with uncertainty bands.  
  - Accounted for both trend and seasonal behavior.  

- **Decomposition**  
  - **Trend**: Gradual growth across the decade.  
  - **Seasonality**: Small recurring fluctuations.  
  - **Residuals**: Unexplained volatility, representing market shocks.  

---

## Visuals
_(to be inserted)_  
- Historical trend plot  
- Regression vs. actual comparison  
- Prophet 2-year forecast  
- Time series decomposition charts  

---

## Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- scikit-learn (Linear Regression)  
- Facebook Prophet (forecasting)  
