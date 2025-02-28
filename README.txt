A Comparative Analysis of LightGBM & XGBoost

Overview

This repository contains a comparative analysis of two popular gradient boosting algorithms, LightGBM and XGBoost, for predicting passenger survival in the Titanic dataset. The project involves data preprocessing, model training, evaluation, and visualization of results to interpret model performance.

Project Files

LGBM & XGB.ipynb – Jupyter Notebook with the implementation and evaluation of both models.

README.txt – This file provides an overview of the project.

Key Features

Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.

Model Training: Hyperparameter tuning and cross-validation for optimal model performance.

Performance Evaluation: Confusion matrices, accuracy scores, and feature importance plots for both models.

Interpretation of Results: Visualizing key features influencing survival predictions.

Results Summary

Confusion Matrix Analysis:

XGBoost performed better in correctly predicting survival cases.

LightGBM showed slightly better overall accuracy but had more false negatives.

Feature Importance:

XGBoost emphasized Sex and Pclass as key predictors.

LightGBM gave higher importance to Fare, Pclass, and Age.

Practical Implications

Understanding feature importance helps in better feature selection and refining predictive models for similar classification problems in real-world datasets.