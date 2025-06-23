 🕒 Time Series Sales Forecasting

This notebook demonstrates a time series forecasting workflow using simulated monthly retail sales data. The goal is to model the trend 
and forecast sales from 2024 to 2030 using Linear Regression after decomposition.
 🧠 What’s Inside

 ✅ Step-by-Step Workflow:
- Simulate monthly sales data (2015–2023) with:
  - Linear trend
  - Seasonal pattern
  - Random noise
- Decompose the time series using `seasonal_decompose`
- Extract the trend component
- Train a Linear Regression model on the trend
- Forecast the next 72 months (6 years)
- Plot historical vs. forecasted data

 🔧 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `statsmodels` (`seasonal_decompose`)
- `sklearn.linear_model` (`LinearRegression`)

 📊 Outputs
- 📉 Decomposition plot (Trend, Seasonality, Residual)
- 🔴 Line plot of forecasted sales vs. historical sales
- 🧾 Printed forecasted values (2024–2030)

 💡 Purpose

This project helps understand:
- How time series data can be broken into components
- The importance of trend modeling
- Forecasting using simple machine learning techniques on decomposed components
  
Made with ⏳ and 💻 by Harneet Kaur
