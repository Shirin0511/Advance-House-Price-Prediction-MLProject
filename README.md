# House Sale Price Prediction 🏠📊

This repository contains an end-to-end Machine Learning regression project that predicts house sale prices based on property features. The project demonstrates a complete ML workflow—from data preprocessing and exploratory analysis to model training and evaluation.


## Problem Statement
Accurately estimating house prices is a common real-world regression problem in real estate and finance. The objective of this project is to build a machine learning model that learns the relationship between house features (such as size, location, and amenities) and their final sale prices.


## Solution Overview
The solution uses supervised machine learning techniques to:
- Analyse historical housing data  
- Engineer and preprocess relevant features  
- Train regression models  
- Evaluate model performance using appropriate metrics  


##  Workflow

### • Data Understanding & Cleaning
Cleaned and prepared the housing dataset by handling missing values and resolving data inconsistencies.

### • Exploratory Data Analysis (EDA)
Analyzed sale price distribution and feature relationships to identify key numerical and categorical drivers.

### • Feature Engineering & Preprocessing
Encoded categorical features and applied a log transformation to stabilize variance and improve model learning.

### • Model Training
Trained regression models using a train-test split to learn patterns in housing price data.

### • Model Evaluation
Evaluated model performance using Root Mean Squared Error (RMSE) on log-transformed sale prices.



## Results & Insights
Achieved an RMSE of ~0.13 on log-transformed house prices, indicating strong predictive accuracy and effective feature learning.



## Tech Stack
- **Programming Language:** Python  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Matplotlib / Seaborn  
  - Scikit-learn  
- **Environment:** Jupyter Notebook  


## Future Improvements
- Feature importance and explainability (SHAP)  
- Model deployment using Flask or FastAPI  
