# BookScan Sales Forecasting with Time Series Analysis and Machine Learning Techniques
**Background Context**
This project focuses on analyzing and forecasting the weekly and monthly sales of two popular books—The Alchemist and The Very Hungry Caterpillar—using real-world sales data from BookScan. The analysis incorporates both classical time series models (like SARIMA) and machine learning models (XGBoost and LSTM), along with hybrid techniques. The objective is to compare the effectiveness of these forecasting methods and identify optimal models for sales prediction.

 **Objective**

The goal of this project is to:

 - Predict future book sales using a combination of classical statistical and machine learning models.

 - Apply decomposition, autocorrelation analysis, and stationarity tests to inform model choice.

 - Evaluate the performance of individual models (ARIMA, XGBoost, LSTM) and their hybrid combinations.

 - Compare forecasting accuracy across weekly and monthly time horizons.

**Key Outcomes**
 - XGBoost consistently achieved the lowest forecasting error (MAPE as low as 8.42%), especially for weekly predictions.

 - SARIMA models performed reliably, particularly for The Alchemist, which showed more predictable sales behavior.

 - LSTM was effective for capturing long-term dependencies but underperformed in some cases due to data characteristics.

 - Hybrid models (SARIMA + LSTM) improved predictions by balancing trend/seasonality and nonlinearity.

 - Monthly forecasts were less accurate than weekly ones, especially for SARIMA, highlighting the benefit of higher-resolution forecasts for dynamic sales patterns.

**Showcased Skills**
 - Time Series Analysis: Seasonal decomposition, ACF/PACF analysis, stationarity testing (ADF), and SARIMA modeling.

 - Machine Learning for Forecasting: Applied XGBoost and optimized using hyperparameter tuning (Grid/Random Search).

 - Deep Learning with LSTM: Built recurrent neural networks and explored hybrid model architectures.

 - Model Evaluation: Used MAPE for performance comparison; built parallel and sequential hybrid models to enhance accuracy.


