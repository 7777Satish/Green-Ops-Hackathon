# Energy Consumption Prediction (AI Hackathon)

## 📌 Overview
This project predicts hourly energy consumption using Random Forest Regression on the Energy Consumption dataset.

## 🚀 Dataset
- Dataset: [Hourly Energy Consumption](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)
- Features: Hour, Day, Month, DayOfWeek
- Target: AEP_MW (Energy Consumption in MW)

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn (RandomForestRegressor, StandardScaler)
- Matplotlib (Visualization)

### Data Preprocessing

Extracted new features from time series data (Hour, Day, Month, DayOfWeek)

Scaled input features using StandardScaler

### Model Selection
Implemented Random Forest Regressor to predict energy consumption

- Handles Non-Linearity – Time series data often has trends & seasonal patterns; Random Forest captures these better.
- Feature Interactions – It considers complex dependencies between features automatically.
- Robust to Noise & Missing Data – Unlike Linear Regression, it handles missing values & outliers well.
- No Need for Stationarity – Works without making the data stationary, unlike traditional linear models.


## 📊 Results
- **Mean Absolute Error (MAE):** ~112
- **Root Mean Squared Error (RMSE):** ~247

## 📦 Dependencies
- os
- numpy
- pandas
- sklearn (RandomForestRegressor, StandardScaler, train_test_split, metrics)
- matplotlib

## Developed by: Satish Singh, Arman Badyal, and Akshit Badyal
