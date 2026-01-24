# Project: Walmart Sales Forecast  
**Overview:**  
Walmart weekly sales forecast.  
Time series supervised learning of regression to predict weekly sales for upcoming 4 weeks.  
Multi steps forecast applied for future prediction.

**Folders:**  
1. Notebook: Jupyter notebook & raw data  
2. Summary: Summary slide  
  
**Analysis flow:**  
1. self-defined problem statement & objective  
2. Data/EDA  
 - Data extraction
 - Data preprocessing
 - EDA
3. Feature engineering  
 - One-hot encoding for holidays
 - Lag features: Weekly sales  
 - Min-Max scalining for LSTM
4. Prediction model  
 - 5 regression models: ARIMA, ElasticNet, Random Forest, Light GBM, LSTM
 - Train/Test data split: hold-out
 - Hyper paramter tuning with train data (for ML models)
 - Model selection based on MAPE from train & test data

**Question or Feedack:**  
digitalfolks55@gmail.com