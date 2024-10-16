# Scores Prediction Based On Study Hours

This repository contains the source code and notebook for a score prediction project. The project demonstrates the process of building a machine learning model to predict final scores based on study hours from the provided dataset.

## Project Overview

In this project, we:
1. Load and explore the dataset.
2. Perform data cleaning and preprocessing.
3. Train and compare multiple machine learning models to predict scores.
4. Evaluate and compare the performance of each model.

The following models are applied and compared:
- **Linear Regression**
- **Decision Tree**
- **Random Forest**

By comparing these models, the goal is to determine which model offers the best performance based on metrics such as accuracy and error rates.

## Key Steps:

- **Data Exploration**: Analyze the dataset using summary statistics and visualizations.
- **Data Preprocessing**: Handle missing data, encode categorical variables, and normalize features.
- **Model Training**: Train Linear Regression, Decision Tree, and Random Forest models on the dataset.
- **Model Evaluation**: Compare models using **R-squared (R²)** and **Mean Squared Error (MSE)** performance metrics.

## Results:
- **Linear Regression**
    - R-squared (R²): 0.9554
    - Mean Squared Error (MSE): 23.5164

- **Decision Tree**
    -   R-squared (R²): 0.8804
    -   Mean Squared Error (MSE): 63.0

- **Random Forest**
    -   R-squared (R²): 0.9299
    -   Mean Squared Error (MSE): 36.9212

The Linear Regression performs best in terms of accuracy, followed by Random Forest and Decision Tree.

## Conclusion
This project shows how to make machine learning for predicting scores based on study hours. Linear Regression is the best model for this dataset.
