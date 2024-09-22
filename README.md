# Time Series Analysis of Electricity Demand in Victoria, Australia (2015-2022)

This repository contains an in-depth analysis of electricity demand data in Victoria, Australia, from 2015 to 2022. 

**Objectives**

The project utilizes the Seasonal Autoregressive Integrated Moving Average (SARIMA) model to forecast future electricity demand and perform a detailed residual and goodness-of-fit analysis.

**Key Features:**

* **Data Preprocessing:** Cleaned and summarized daily electricity demand data into monthly observations.
* **Visualization:** Time series plots, Q-Q plots, and ACF/PACF plots to analyze trends, seasonality, and stationarity.
  * Time series plot of Electricity Demand Series: ![image](https://github.com/user-attachments/assets/58edc823-8ff5-40c8-94e2-7829535ac369)

* **Modeling:** Tested several SARIMA models with different parameters (e.g., SARIMA(4,0,5)x(0,1,1), SARIMA(1,0,3)x(0,1,1)).
* **Residual and Statistical Tests:** Augmented Dickey-Fuller, Phillips-Perron, and Shapiro-Wilk tests to assess model performance and stationarity.
* **Forecasting:** Used the best SARIMA models to forecast future electricity demand.
  * ![image](https://github.com/user-attachments/assets/1eedc284-250f-44cd-865c-c7883f2c0748)


**Tools and Techniques:**
* R for data preprocessing, visualization, and modeling.
* SARIMA model implementation for time series forecasting.
* Goodness-of-fit metrics including AIC, BIC, and residual diagnostics.
