# Project: RUL prediction for turbofan jet engine  
**Overview:**  
Supervised learning of Regression to predict RUL of turbofan jet engines.
Brought several assumptions for the self-defined problem statement.
These could be not correct; Owner does not have deeper understanding on engine maintenance process.
Take them as just assumptions.

**Folders:**  
1. Notebook: Jupyter notebook & raw data  
2. Summary: Summary slide  
  
**Analysis flow:**  
1. self-defined problem statement & objective  
2. Data/EDA & Feature engineering  
 - Data extraction
 - EDA
 - Feature selection
 - Normalization
 - Clipping RUL on train data
3. Predictive model  
 - 6 regression models: Linear, ElasticNet, SVR, RF, LGBM & XGB
 - Train data split into train & validation data
 - Hyper paramter tuning with train data
 - Model selection based on MSE with train & validation data
 - Prediction with test and evaluation 

**Question or Feedack:**  
digitalfolks55@gmail.com