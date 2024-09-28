# Domino's Time Series Forecasting Project

## Overview
This project involves developing time series forecasting models to predict the sales of various pizza types from Domino's. Using historical sales data, different modeling techniques including ARIMA, SARIMA, Prophet, and XGBoost are employed to analyze and forecast future sales.

## Table of Contents
- [Project Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Sales Data](#sales-data)
- [Time Series Analysis](#time-series-analysis)
- [Forecasting](#forecasting)
- [Results](#results)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Requirements
- **Python 3.x**
- **Pandas**
- **NumPy**
- **Statsmodels** (for ARIMA/SARIMA)
- **Prophet**
- **XGBoost**
- **Seaborn** (for visualizations)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/ShabanaBacker/dominos-time-series-forecasting.git
   cd dominos-time-series-forecasting
## Install the required Python packages:
bash
Copy code
pip install pandas numpy statsmodels prophet xgboost matplotlib seaborn

## Sales Data
The Pizza_sale_new.csv file contains historical sales data for different pizza types, including the following columns:

- pizza_id: Unique identifier for each pizza type
- date: Date of the sales record
- quantity: Quantity of pizzas sold

## Time Series Analysis
This Jupyter notebook contains steps for data preprocessing, model training, evaluation, and forecasting.

## Model Training
- ARIMA/SARIMA: Train ARIMA and SARIMA models using the statsmodels library.
- Prophet: Utilize the Prophet library for forecasting, suitable for handling seasonality and trends.
- XGBoost: Implement XGBoost for regression modeling based on historical sales data.

## Evaluation
 - Calculate Mean Absolute Percentage Error (MAPE) to evaluate model performance.
 - Select the best-performing model for each pizza based on the lowest MAPE.
## Forecasting
After selecting the best model for each pizza type, the notebook generates forecasts for the next week and saves the results.
## Usage
Run the notebook:
jupyter notebook dominos_time_series_forecasting.ipynb

