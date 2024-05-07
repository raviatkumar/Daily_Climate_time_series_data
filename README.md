Summary:

1. Project Title: Daily Climate Time Series Data
2. Objective: Construct a weather forecasting model tailored for climate analysis, utilizing a dataset covering the period from January 1, 2013, to April 24, 2017. Key parameters include meantemp, humidity, wind_speed, and meanpressure.
3. Data Analysis: Conducted Augmented Dickey-Fuller (ADF) tests to assess stationarity, revealing that meantemp is likely non-stationary while humidity, wind_speed, and meanpressure are likely stationary. Explored autocorrelation function (ACF) and partial autocorrelation function (PACF) plots to understand time series dependencies.
4. Model Development: Utilized SARIMAX model to forecast mean temperature based on the dataset, specifying parameters (0, 1, 0) for the non-seasonal part and (0, 1, 0, 12) for the seasonal part.
5. Performance Metrics: Calculated Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) to quantify the accuracy of the SARIMAX model's predictions.
6. SARIMA Model: Evaluated SARIMA model's ability to capture seasonal patterns and overall temperature trends, noting some discrepancies between actual and forecasted temperature data.

Conclusion:

1. The project successfully developed and evaluated a SARIMAX model for forecasting mean temperature in Delhi based on historical climate data.
2. ADF tests indicated stationarity of humidity, wind_speed, and meanpressure, while meantemp required further transformation for stationarity.
3. ACF and PACF plots provided insights into short-term dependencies and guided the choice of SARIMAX model parameters.
4. SARIMAX model evaluation revealed satisfactory performance in capturing temperature variations, with reasonable accuracy indicated by low MAE, MSE, and RMSE values.
5. While the SARIMA model showed potential in capturing seasonal patterns, some discrepancies between actual and forecasted temperature data were observed, highlighting areas for model improvement.

Overall, the project contributed to climate analysis by providing insights into temperature forecasting and modeling techniques, with potential for further refinement and application in weather prediction and climate research.
