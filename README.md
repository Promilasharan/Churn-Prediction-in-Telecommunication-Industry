# Telecommunication Customer Churn Prediction
## Introduction
Telecommunication industry is one of the rapidly growing industries globally and customer churn is a significant problem for the industry. Churn refers to the loss of customers and predicting which customers are likely to churn can help the company to take proactive measures to retain them.

This project is focused on using machine learning algorithms to predict customer churn in the telecommunication industry. The project uses the 'WA_Fn-UseC_-Telco-Customer-Churn' dataset from Kaggle to build the prediction model.

## Dataset
The 'WA_Fn-UseC_-Telco-Customer-Churn' dataset contains information about 7043 customers and various features such as customer demographics, services subscribed, and billing information.

## Exploratory Data Analysis
An exploratory data analysis was performed on the dataset to gain insights into the data. The analysis helped to understand the distribution of various features and detect any missing or irrelevant data.

## Model Building
Two machine learning algorithms were used to build the churn prediction model:

- Decision Tree Classifier
- Random Forest Classifier
The models were built using the original dataset and a curated dataset using the Synthetic Minority Over-sampling Technique (SMOTEEN). The SMOTEEN technique was used to balance the class distribution in the dataset.

## Model Comparison
The performance of the two models was compared using various metrics such as accuracy, precision, recall, and F1 score. The Random Forest Classifier with the SMOTEEN dataset performed the best and was chosen as the final model.

## Model Deployment
The final model was saved in the Pickle format and used to build a web application using Flask. The web application has a home page (home.html) and a back-end script (app.py) that takes inputs from the user and generates a churn prediction based on the input data.

## Conclusion
In conclusion, this project demonstrates the use of machine learning algorithms for customer churn prediction in the telecommunication industry. The project highlights the importance of data curation and the impact it can have on the performance of the prediction model. The web application built using Flask provides a user-friendly interface for generating churn predictions, making it easier for telecommunication companies to predict and prevent customer churn.
