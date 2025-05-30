# Power-Forecasting-using-ML

# Overview

This project demonstrates how to forecast power consumption in France using historical data from the RTE (Réseau de Transport d'Électricité) API and the XGBoost machine learning algorithm. The solution provides a 3-month forecast of power consumption patterns based on historical data.

# Features

- Data Collection: Retrieves historical power consumption data from the RTE API
- Data Processing: Cleans and prepares the data for machine learning
- Forecasting Model: Uses XGBoost for time series forecasting
- Visualization: Includes data visualization of historical and predicted consumption
- API Integration: Handles authentication and data retrieval from RTE's API

# Data Sources

- Historical power consumption data from RTE API
- The data includes half-hourly consumption values with timestamps

# Methodology

- Data Collection: Retrieve historical power consumption data from RTE API
- Feature Engineering: Create time-based features (hour of day, day of week, etc.)
- Model Training: Train XGBoost on historical data
- Forecasting: Generate predictions for future time periods
- Evaluation: Assess model performance using RMSE

# Results

The model provides:

- 3-month forecasts of power consumption
- Visualization of historical vs predicted values
- Performance metrics to evaluate forecast accuracy
