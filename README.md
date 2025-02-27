# Weather Forecasting using Machine Learning

## Project Overview
This project focuses on predicting weather conditions using various machine learning models. It utilizes data from the **Kelmarsh wind farm**, including turbine data, status data, and ERA5 weather data. The primary objective is to develop a model that minimizes forecasting errors and enhances prediction accuracy. The **Root Mean Squared Error (RMSE)** is used as the primary evaluation metric.

## Dataset
The dataset consists of six different sources, including:
- Turbine data
- Status data
- Kelmarsh ERA5 weather data

## Features Used
- **Weather-related parameters** (e.g., temperature, wind speed, pressure)
- **Time-series features** (e.g., timestamps, historical trends)
- **Operational data** from turbines

## Models Implemented
The following machine learning models were used and compared based on their RMSE scores:

1. **CatBoost** - Gradient boosting model optimized for categorical data.
2. **LightGBM** - Efficient gradient boosting framework optimized for speed.
3. **Random Forest** - Ensemble learning method using multiple decision trees.
4. **Decision Tree** - Simple tree-based model for making predictions.
5. **K-Nearest Neighbors (KNN)** - Distance-based model using nearest data points.
6. **Lasso Regression** - Regularized regression technique reducing complexity.
7. **Linear Regression** - Baseline model for trend estimation.
8. **Naive Forecaster** - Simple forecasting model used for benchmarking.

## Model Evaluation
The models were evaluated using **RMSE**, which is suitable for this problem because:
- It penalizes larger errors more than smaller ones.
- It provides an interpretable measure in the same unit as the target variable.
- It effectively captures forecasting accuracy.

**MAE Scores (Scaled to Single Digits):**
| Model            | MAE Score |
|-----------------|----------|
| CatBoost       | 7.22     |
| LightGBM       | 7.57     |
| Random Forest  | 8.15     |
| Decision Tree  | 8.92     |
| KNN            | 10.17    |
| Lasso          | 10.30    |
| Linear         | 8.79     |
| Naive Forecaster | 2.06   |


## Future Improvements
- Fine-tuning hyperparameters for better model performance.
- Exploring deep learning models (e.g., LSTMs) for time-series forecasting.
- Adding explainability using SHAP values for feature importance analysis.

## Contributors
- **Nisshanth V G**
  - Department of Computational Intelligence,
  - SRM Institute of Science and Technology, Tamil Nadu, India.
- **Nevin Haniel R**
  - Department of Computational Intelligence,
  - SRM Institute of Science and Technology, Tamil Nadu, India.
- **Yuvan Nagalingam H**
  - Department of Computational Intelligence,
  - SRM Institute of Science and Technology, Tamil Nadu, India.



