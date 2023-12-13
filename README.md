# Comprehensive Water Quality Assessment and Potability Prediction using Multi-parameter Analysis

## Introduction
This machine learning problem aims to predict water potability based on provided water quality parameters. By analyzing relevant features, the objective is to develop a model that classifies water samples as meeting or not meeting potability standards. The significance lies in ensuring the safety of water for consumption, contributing to environmental and public health concerns.

## Problem Statement
This machine learning problem seeks to predict water potability by analyzing a set of water quality parameters. The goal is to determine whether the provided features indicate compliance with potability criteria, highlighting the importance of ensuring safe water for consumption.

## Overview of Dataset
![Picture1](https://github.com/Vineeiee2291/Water-Potability-classification/assets/118652081/ae0bc8ee-297f-4641-b5b8-937ac0df823c)

## Data Science Process
1. Project Overview

2. Data Exploration

3. Data Cleaning

4. Exploratory Data Analysis

5. Data Preprocessing

6. Model Building & Evaluation

## Distribution of Features with respect to Potability
![Dist wrt target](https://github.com/Vineeiee2291/Water-Potability-classification/assets/118652081/61c02373-0667-4f4e-8ab8-f3be2e6e9141)

## Pairplot
![Pairplot](https://github.com/Vineeiee2291/Water-Potability-classification/assets/118652081/f3908aa3-9e7f-45cf-890d-61619ace878b)

## Feature Correlation
![correlation](https://github.com/Vineeiee2291/Water-Potability-classification/assets/118652081/6b2e73ae-58f3-4bdb-9ac9-259825f42768)

## Machine Learning Models Used
1.LogisticRegression - A linear classification model.

2.GaussianNB - A Gaussian Naive Bayes classifier for probabilistic classification.

3.SVC - Support Vector Classifier for classification tasks.

4.DecisionTreeClassifier - A decision tree-based classifier.

5.RandomForestClassifier - A random forest ensemble classifier.

6.AdaBoostClassifier - A classifier using AdaBoost boosting technique.

7.GradientBoostingClassifier - A classifier using gradient boosting.

8.XGBClassifier - XGBoost, a popular gradient boosting library for classification and regression tasks.

## Evaluation Results
![Screenshot (55)](https://github.com/Vineeiee2291/Water-Potability-classification/assets/118652081/91987e6c-5d25-450d-a5cc-9e5c457b279d)

## Final Model using RandomForest
![Picture2](https://github.com/Vineeiee2291/Water-Potability-classification/assets/118652081/08ded7e6-6213-426a-b65c-555c48c5f276)

## Confusion Matrix
![cm](https://github.com/Vineeiee2291/Water-Potability-classification/assets/118652081/c528b07a-4f18-49ab-9d66-bdf3ee7a9cb8)

## ROC Curve
![auc](https://github.com/Vineeiee2291/Water-Potability-classification/assets/118652081/300a5b7e-c64b-41fe-b813-c34ab2c06196)

## Feature Importance
![FI](https://github.com/Vineeiee2291/Water-Potability-classification/assets/118652081/990d1ad9-25db-45fc-a7b1-6ef1a6733f6e)

## Cross Validation
### Standard Deviation
- The standard deviation is relatively small, indicating that the model's performance is consistent across different subsets of the data.
### Mean Accuracy
- The mean accuracy of approximately 89.32% suggests that, on average, your model is correctly predicting the target variable with this level of accuracy.


