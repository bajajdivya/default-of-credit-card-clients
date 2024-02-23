# Credit Default Prediction Project

## Overview
This project aims to predict the likelihood of defaulting on credit card payments based on various features such as credit limit, age, education, payment history, and more. The project includes data analysis, visualization, and the implementation of machine learning models for prediction.

## Data
The dataset used for this project is sourced from credit card clients and contains information about their credit history, demographic details, and payment behavior. Initial data cleaning and preprocessing were performed to prepare the dataset for analysis and model training.

## Exploratory Data Analysis
The exploratory data analysis (EDA) involved visualizations to understand patterns and relationships within the data. Notable visualizations include violin plots and box plots illustrating the distribution of credit limits based on gender and age, and bar charts showing the proportion of default payments by education level and gender.

## Feature Engineering
To enhance the dataset, additional features were created, such as aggregating bill amounts and paid amounts across different months. This provided a more comprehensive view of the client's financial behavior.

## Machine Learning Models
Several machine learning classifiers were employed, including Logistic Regression, Random Forest, Decision Tree, Naive Bayes, K-Nearest Neighbors, and Support Vector Machine. These models were trained on a subset of the data and evaluated based on accuracy and F1 score.

## Results
The models achieved varying levels of accuracy and F1 scores, with Support Vector Machine showing the highest accuracy. Confusion matrices were generated to visualize the performance of each model in predicting default and non-default instances.

## Conclusion
This project provides insights into the factors influencing credit default and demonstrates the effectiveness of machine learning models in predicting default outcomes. The findings can be valuable for financial institutions in assessing credit risk and implementing proactive measures to minimize defaults.

Feel free to explore the Jupyter notebooks for a detailed understanding of the analysis and model implementations.
