House Sale Price Prediction using XGBoost-

An end-to-end machine learning project predicting house prices using advanced regression techniques.  
This project includes complete data preprocessing, Exploratory Data Analysis (EDA), feature engineering, hyperparameter tuning using GridSearchCV, model evaluation using RMSE and final prediction generation for Kaggle submission.


Technologies Used-
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-Learn
- XGBoost
- GridSearchCV
- Jupyter Notebook

Workflow-

1. Load data and clean missing values  
2. Exploratory Data Analysis  
3. Feature engineering + log transform  
4. One-hot encoding  
5. Hyperparameter tuning (GridSearchCV)  
6. Train final model and generate predictions  
7. Create Kaggle submission file

Submission Code Example

test_pred_log = best_model.predict(X_test)
test_pred = np.exp(test_pred_log)

submission = pd.DataFrame({
    "Id": test_data["Id"],
    "SalePrice": test_pred
})
submission.to_csv("submission.csv", index=False)


Suggested Folder Structure

HousePricePrediction/
│
├── HouseSalePricePrediction.ipynb
├── README.md
├── submission.csv
└── requirements.txt


Model Performance
RMSE (Validation, log scale): 0.1313

Author
Shirin Gupta
https://www.linkedin.com/in/shirin-gupta-387899191/
Shirin.gupta05@gmail.com
