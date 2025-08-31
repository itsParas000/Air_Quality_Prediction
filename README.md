### Project Overview
This project implements an air quality prediction model using machine learning techniques, specifically the Prophet time-series forecasting model. The goal is to predict carbon monoxide (CO) levels based on historical air quality and weather data from the UCI Machine Learning Repository.

### Dataset
Source: UCI Machine Learning Repository - Air Quality Data Set
File: AirQualityUCI.xlsx

### Libraries Required:
1. Data Manipulation and Analysis:  
   o pandas  
   o numpy  
2. Data Visualization:  
   o matplotlib  
   o seaborn  
3. Machine Learning:  
   o scikit-learn  
4. Forecasting:  
   o fbprophet  


### Feature Engineering  
Retained key columns (e.g., CO(GT), NOx(GT), T, RH).  
Set datetime as the index and scaled numeric data using StandardScaler.  

### Model Development  
Split data into 80% training and 20% testing sets.  
Trained a Prophet model with yearly, weekly, and daily seasonality on CO(GT).  
