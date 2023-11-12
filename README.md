# Machine-Learning---Employee-Turnover-Analytics

Table Of Contents:

- Introduction
- About the Dataset
- Python libraries used
- Project Work flow
- Purpose of the wrok


# Introduction

Portobello Tech is an app innovator that has devised an intelligent way of predicting employee turnover within the company. It periodically evaluates employees' work details including the number of projects they worked upon, average monthly working hours, time spent in the company, promotions in the last 5 years, and salary level.

Data from prior evaluations show the employee’s satisfaction at the workplace. The data could be used to identify patterns in work style and their interest to continue to work in the company.

The HR Department owns the data and uses it to predict employee turnover. Employee turnover refers to the total number of workers who leave a company over a certain time period.


# About the Dataset

Dataset Information

Number of instances: 14999

Number of attributes: 10

Column Name	Description
- satisfaction_level -->	satisfaction level at the job of an employee
- last_evaluation	--> Rating between 0 to 1, received by an employee at his last evaluation
- number_project --> Number of projects, an employee involved in
- average_montly_hours --> Average number of hours in a month, spent by an employee at office
- time_spend_company --> Number of years spent in the company
- Work_accident	--> 0 - no accident during employee stay, 1 - accident during employee stay
- left --> 0 indicates employee stays in the company, 1 indicates - employee left the company
- promotion_last_5years	--> Number of promotions in his stay
- Department --> Department, an employee belongs to
- salary --> Salary in USD


# Different Python libraries used to complete this EDA:

Pandas

NumPy

Matplotlib.Pyplot

Seaborn

Scipy

sklearn.cluster

sklearn.linear_model

sklearn.model_selection

sklearn.metrics

sklearn.ensemble

# Project Work flow

Importing Libraries

Loading the Dataset

Explore Dataset

Data Cleaning and manipulate

Handling Outliers

Data Visualization

LogisticRegression

RandomForestClassifier

GradientBoostingClassifier

Conclusion

# The purpose of the analysis

The purpose of the project is to analyze and predict employee turnover within a company using machine learning techniques. The steps involved are as follows:

1. Perform data quality check.
2. Conduct exploratory data analysis to understand factors contributing to turnover.
3. Cluster employees who left based on satisfaction and evaluation.
4. Address class imbalance using the SMOTE technique.
5. Perform 5-fold cross-validation and train models (Logistic Regression, Random Forest, Gradient Boosting).
6. Evaluate models using ROC/AUC scores, ROC curves, and confusion matrices.
7. Determine the appropriate evaluation metric (recall or precision) based on the confusion matrix.
8. Provide retention strategies for targeted employees.

The goal is to identify the best model for predicting turnover and offer insights to retain valuable employees.
