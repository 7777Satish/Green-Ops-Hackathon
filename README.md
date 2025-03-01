# Energy Consumption Prediction (AI Hackathon)
Deployment: https://green-ops-hackathon-deployment-1.onrender.com
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

## Deployment User Guide
Deployment: https://green-ops-hackathon-deployment-1.onrender.com
**Postman**, **cURL**, or any HTTP client to send a request.

### **Endpoint**
\`\`\`bash
POST /predict
\`\`\`

### **Request Body (JSON Format)**
\`\`\`json
{
  "Hour": 12,
  "Day": 15,
  "Month": 3,
  "DayOfWeek": 4
}
\`\`\`

### **Response Example**
\`\`\`json
{
  "Predicted Load (MW)": 24567.89
}
\`\`\`

## Developed by: Satish Singh, Arman Badyal, and Akshit Badyal
