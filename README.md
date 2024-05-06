# Daily Climate time series data

This project aims to construct a weather forecasting model tailored for the Indian climate, utilizing a dataset spanning from January 1, 2013, to April 24, 2017, in Delhi. The parameters - meantemp, humidity, wind_speed, and meanpressure - play a crucial role. Acquired from Weather Underground API, the dataset is central to Assignment 4 of the 2019 Data Analytics Course at PES University, Bangalore. The goal involves data exploration, preprocessing, and the development and evaluation of a machine learning model.


## Summary:

1. Project Title: Daily Climate Time Series Data
2. Objective: Construct a weather forecasting model for Delhi using a dataset spanning from January 1, 2013, to April 24, 2017, including parameters like meantemp, humidity, wind_speed, and meanpressure.
3. Data Source: Weather Underground API.
4. Data Exploration: Analyzed seasonal patterns, upward trends, and distribution characteristics of temperature, precipitation, wind speed, and CO2 concentrations.
5. Model Development: Utilized SARIMAX model for temperature forecasting.
6. Model Evaluation: Evaluated the SARIMAX model using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
7. Model Performance: The SARIMAX model demonstrated reasonable accuracy in temperature predictions, with MAE of approximately 3.82, MSE of approximately 5.04, and RMSE of approximately 5.04.

## Conclusion:

1. The SARIMAX model effectively captured seasonal patterns and upward trends in temperature data.
2. It provided valuable insights into temperature anomalies, CO2 concentrations, and wind speed variations.
3. The ACF and PACF plots indicated short-term dependency in temperature data, supporting the choice of SARIMAX model.
4. The SARIMAX results revealed significant autocorrelation at lag 1, suggesting a strong correlation between consecutive temperature values.
5. Despite some discrepancies between actual and forecasted temperatures, the SARIMAX model demonstrated overall satisfactory performance in temperature forecasting.

Overall, the SARIMAX model proved to be a valuable tool for analyzing and forecasting temperature variations in Delhi's climate dataset, providing actionable insights for weather prediction and climate analysis.
