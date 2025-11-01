🧠 Boston Housing Price Prediction

📘 Project Overview

This project implements Linear Regression from scratch using the Boston Housing dataset to predict the median value of owner-occupied homes (MEDV) based on various socio-economic and geographic factors.

It focuses on understanding the mathematical foundations of regression, performance evaluation, and practical data preprocessing techniques.

🧩 Concepts & Skills Learned

Data Loading and Exploration:

Reading CSV data with pandas

Understanding dataset structure using .info(), .describe(), and visual analysis with matplotlib

Data Preprocessing:

Handling missing values

Feature-target separation (X and y)

Splitting data into training and testing sets (80/20 ratio)

Linear Regression (From Scratch):

Adding an intercept column

Computing model coefficients using the Normal Equation

Making predictions on training and testing data

Error Metrics & Evaluation:

MSE (Mean Squared Error)

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² Score (Coefficient of Determination)

Model Interpretation:

Understanding how each feature affects the target variable (MEDV)

Exploring correlation through scatter plots (LSTAT vs MEDV)

Function Implementation:

Writing a reusable prediction function:

Includes input scaling using mean and standard deviation of training data for realistic predictions.

📊 Results Summary

Successfully implemented a working linear regression model without using Scikit-learn.

Verified model performance through multiple evaluation metrics.

Observed an inverse relationship between poverty rate (LSTAT) and house prices (MEDV).

Implemented a custom prediction function for unseen data.

🧮 Tools & Libraries Used

Python

NumPy

Pandas

Matplotlib
