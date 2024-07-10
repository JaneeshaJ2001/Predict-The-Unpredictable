# Time-Series-Weather-Prediction
Predicta 1.0 : Public leaderboard 4th Place Solution Overview

RMSE Score : 2.4717

## Overview
This repository contains the code and resources for my time series forecasting project focused on predicting average temperatures for the first week of 2019 across 100 cities worldwide. The project utilizes historical weather data and implements a hybrid modeling approach combining sinusoidal regression and XGBoost for improved accuracy.

## Data Preprocessing

The dataset underwent rigorous preprocessing to handle missing values using forward filling, interpolation, and leveraging last year's temperatures where applicable. 

## Feature Engineering

Feature engineering focused on creating time indices, sinusoidal transformations to capture seasonal patterns, and ensuring data consistency across different cities. Additional features were engineered to improve model performance and capture relevant weather patterns.

## Modeling

The core of the project involves a hybrid model:

- SinusoidalRegressor: Custom regression model capturing seasonal variations using sine and cosine transformations of time.
- BoostedHybrid: Combination of SinusoidalRegressor and XGBoost for handling residual complexities and improving forecasting accuracy.
The modeling process includes hyperparameter tuning and cross-validation to optimize model performance.

## Evaluation Metrics

Evaluation metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) were used to assess model accuracy. These metrics were calculated across different cities and for various time periods to validate the robustness of the models.

## Results

The hybrid model demonstrated significant improvements in forecasting accuracy compared to baseline models. 
