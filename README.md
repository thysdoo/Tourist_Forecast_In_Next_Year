# Tourist_Forecast_In_Next_Year

**Objective**:
Predict the number of tourists visiting Singapore for the next 12 months using the singapore_tourist_new.csv dataset.

**Contributions**:	
- Exploratory Data Analysis (EDA):
Libraries used: Pandas, NumPy, Matplotlib, Seaborn.
Insights:
The dataset does not have duplicates, missing values, or outliers.
The line plot revealed that the number of tourists shows clear seasonal patterns with peaks and troughs at regular intervals, indicating seasonal behavior.
Key features identified from EDA:
Trend: The data shows an overall increasing trend in tourist numbers over time;
Seasonality: Clear seasonal patterns with peaks and troughs at regular intervals suggest the presence of seasonal effects;
Resid (Residuals): There is some noise in the data, but the noise level is relatively low.

- Data Preprocessing:
Handled missing values (none detected) and ensured the data was clean and ready for modeling.
Applied necessary transformations (e.g., differencing) to stabilize variance and achieve stationarity where required.
Model Building and Evaluation:
Used Time Series Forecasting models including:
ARIMA (AutoRegressive Integrated Moving Average): Modeled the trend and seasonality in the data;
Exponential Smoothing (Holt-Winters): Applied to capture the seasonal and trend components effectively;
Evaluated models using RMSE (Root Mean Square Error) and MAE (Mean Absolute Error) for accuracy in predicting future values.
Forecasted the number of tourists for the next 12 months, achieving a RMSE of X and an MAE of Y.

- Evaluation and Insights:
Key insights: The data demonstrates a clear seasonal pattern with higher tourist numbers in certain months, likely due to holidays and events. The forecast for the next 12 months indicates a continued steady increase in tourist arrivals, with seasonal peaks.
The model’s ability to capture trend and seasonality will aid in planning for marketing and infrastructure requirements.

- Visualization and Reporting:
Created interactive visualizations of actual vs predicted values to showcase the performance of the forecasting models.
Delivered a structured report summarizing the methodology, evaluation metrics, and forecast insights for stakeholders.

**Tools Used**:
Python (Jupyter Notebook), Time Series Forecasting (ARIMA, Exponential Smoothing), Visualization (Matplotlib, Seaborn)
