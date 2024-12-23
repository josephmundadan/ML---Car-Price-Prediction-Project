# ML---Car-Price-Prediction-Project

#Car Price Prediction Project

This repository contains the implementation of a car price prediction model for analyzing factors affecting car prices in the American market. The primary goal is to identify the significant variables that influence car pricing and develop a reliable predictive model.

# Problem Statement

A Chinese automobile company intends to enter the US market by setting up local manufacturing units. To understand the pricing dynamics, they contracted a consulting firm to analyze key factors affecting car prices. This analysis will assist in:

Identifying variables significant in predicting car prices.

Evaluating how well these variables explain car pricing.

# Dataset

The dataset contains various features of cars including technical specifications, categorical attributes, and the target variable (price).

# Objectives

Load and preprocess the dataset.

Implement multiple regression models:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor

Compare the performance of models based on evaluation metrics:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

R-squared (R²)

Identify significant features affecting car prices.

Perform hyperparameter tuning to optimize the best-performing model.

# Implementation

Steps:

# Data Preprocessing:

Checked for missing values.

Encoded categorical variables using one-hot encoding.

Standardized numerical features using StandardScaler.

Split the dataset into training and testing sets.

# Model Training and Evaluation:

Implemented and evaluated the following regression models:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor

Compared the models based on MSE, MAE, and R².

# Feature Importance Analysis:

Used the Random Forest model to determine significant features affecting car prices.

# Hyperparameter Tuning:

Tuned the Random Forest Regressor using Grid Search for optimal parameters.

# Results

# Performance Metrics:

A summary of MSE, MAE, and R² scores for each model is provided.

# Feature Importance:

The top 10 features influencing car prices were identified, including:

Engine size

Curb weight

Highway mpg

# Best Model:

The Random Forest Regressor performed the best after hyperparameter tuning.

# Contributing

Contributions are welcome! Please submit a pull request or open an issue for suggestions and bug fixes.

# License

This project is licensed under the MIT License. See the LICENSE file for details.
