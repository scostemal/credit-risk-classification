# Credit Risk Classification

## Analysis

* The primary goal of this analysis is to predict the status of loans as either healthy`(0)` or high-risk`(1)` based on a set of features provided in the `lending_data.csv` This predicitive model can assist financial institutions in making informed decisions regarding loan approvals, thereby reducing the risk of default.

* The dataset contained in `lending_data.csv` encompasses various financial indicators and personal information related to borrowers such as loan amount, interest rates, and credit scores. The goal was to predict the `loan_status` variable, indicating whether a loan would likely be healthy or high-risk.

* 3 stages of machine learning were used - Data Preprocessing, Model Training, Model Evaluation. Data preprocessing involved splitting the dataset into features (X) and target variable (y) followed by splitting into a training and testing set. A logistic regression model was trained on the dataset. The model's performance was assessed by using a confusion matrix and classification report. 

## Performance Metrics
* Accuracy Scores:
    * Logistic Regression: 99%
* Precision and Recall Scores (for high-risk loans):
    Logistic Regression:
        * Precision: 0.85
        * Recall: 0.91

## Summary

The logistic regression model demonstrated high accuracy in predicting the loan status indicating the models effectiveness in correctly identifying both healthy and high-risk loans. 

I would recommend this logistic regression model as a valuable tool for lenders in risk assessment. 
