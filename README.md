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


## 📊 Results
- **Mean Absolute Error (MAE):** ~112 MW  
- **Root Mean Squared Error (RMSE):** ~247 MW  

## 📦 Dependencies
- os
- numpy
- pandas
- sklearn (RandomForestRegressor, StandardScaler, train_test_split, metrics)
- matplotlib

## Developed by: Satish Singh, Arman Badyal, and Akshit Badyal