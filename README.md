# EthereumPrice-Prediction

## Overview
This project aims to predict Ethereum's price by leveraging two models: **LSTM (Long Short-Term Memory)** and **ARIMA (Auto-Regressive Integrated Moving Average)**. It evaluates the performance of both models and forecasts future price trends.

---

## Implementation and Experimentation

### 1. LSTM Model
#### a. Model Building
- Implemented using **TensorFlow/Keras**.
- Sequential model with LSTM layers, dropout for regularization, and dense output layer.
- Hyperparameter tuning to optimize performance.

#### b. Model Evaluation
- Metrics used:
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R² Score
- Training and validation loss monitored to prevent overfitting.

#### c. Prediction
- Predicted Ethereum's price for the next **30 days** based on test data.

### 2. ARIMA Model
#### a. Model Building
- Developed using **statsmodels**.
- Order of the ARIMA model determined through ACF and PACF plots.

#### b. Model Evaluation
- Metrics used:
  - RMSE, MAE, MSE
  - Explained Variance Regression Score
  - R² Score
- Comparison plot: Actual vs. Predicted prices.

#### c. Prediction
- Generated **30-day forecast** for Ethereum's price.

---

## Results
- **LSTM Performance**:
  - Training Loss: _[value]_
  - Validation Loss: _[value]_
  - RMSE: _[value]_
  - R² Score: _[value]_

- **ARIMA Performance**:
  - RMSE: _[value]_
  - MAE: _[value]_
  - R² Score: _[value]_

- **30-Day Forecast**:
  - LSTM: Visualization of predicted trends with confidence intervals.
  - ARIMA: Forecast compared against the latest actual price trends.

---

## Conclusion
Both models demonstrate strengths in predicting Ethereum price trends:
- **LSTM** excels in capturing non-linear patterns.
- **ARIMA** performs well for linear time-series data.

Future work may include integrating additional features (e.g., trading volume, social sentiment) to enhance predictive accuracy.

---

## Visualizations
- Plot: Actual vs. Predicted Prices (LSTM & ARIMA)
- Forecast: 30-Day Price Prediction

---

## References
1. TensorFlow Documentation - [Link](https://www.tensorflow.org/)
2. Statsmodels Documentation - [Link](https://www.statsmodels.org/)
