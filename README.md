Project Overview:-

This project predicts whether a customer will leave a telecom company based on customer demographics, subscription details, billing information, and service usage

Problem Statement:-

Customer churn negatively impacts business revenue. The goal is to identify customers likely to churn so retention strategies can be applied.

Dataset:-

Records: 7043
Features: 21
Target Variable: Churn (Yes/No)


Technologies Used:-

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Data Analysis Process
Data Cleaning
Missing Value Handling
Exploratory Data Analysis
Feature Engineering
Model Training
Model Evaluation
Models Used
Model	Accuracy
Logistic Regression	81%
Random Forest	79%
Final Selected Model

Logistic Regression:-
Reason:

Highest accuracy
Better interpretability
Faster training
Key Findings
Month-to-month contracts show higher churn.
Customers with short tenure are more likely to churn.
High monthly charges increase churn probability.
Long-term contracts reduce churn.
Feature Importance

Top influential features:

Contract Type
Tenure
Monthly Charges
Total Charges
Internet Service

Future Improvements:-
XGBoost
Hyperparameter Tuning
Deep Learning Models
Deployment using Streamlit
