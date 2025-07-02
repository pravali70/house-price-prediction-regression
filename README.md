# 🏠 House Price Prediction (Per Unit Area) - Mini Project
👋 Welcome to this machine learning project focused on predicting residential property prices per unit area!

## 📝 Project Overview
In this project, we analyze a real-world dataset containing details of residential property transactions. The dataset includes both structural and geographic features such as:

Transaction Date

House Age

Distance to the Nearest MRT Station

Number of Nearby Convenience Stores

Geographic Coordinates (Latitude & Longitude)

The target variable is the House Price per Unit Area, and our goal is to build a machine learning pipeline that predicts this value accurately.

## 🎯 Objective
The main objective is to build and evaluate regression models to predict the price per unit area of a house based on its attributes.

This predictive model supports:

Buyers in evaluating fair prices

Sellers in setting competitive pricing

Real estate analysts in market trend forecasting

Developers and investors in project planning

## 🤖 Models Evaluated
We experimented with and compared the following regression models:

Multiple Linear Regression

Polynomial Regression

Support Vector Regression (SVR)

Random Forest Regressor

Tuned Random Forest Regressor

XGBoost Regressor

These models help uncover both linear and nonlinear relationships between features and house pricing.

## 📊 Evaluation Metrics
To assess and compare model performance, we use standard regression metrics:

MAE (Mean Absolute Error) – Measures average absolute differences

MSE (Mean Squared Error) – Penalizes larger errors

RMSE (Root Mean Squared Error) – Interpretable measure of overall model error

These metrics ensure we evaluate both accuracy and robustness of the models.

## 🧰 Tools & Libraries
This project is implemented in Python using:

pandas – Data loading and preprocessing

numpy – Numerical computations

matplotlib & seaborn – Visualizations and trend analysis

scikit-learn – Model building and evaluation

xgboost – Gradient boosting regressor

scipy – For optimization and fine-tuning

## ✅ Outcome
Through this project, we aim to:

Identify the best-performing regression model for house price prediction

Understand the key features influencing real estate prices

Provide data-driven insights for better real estate valuation and decision-making

Build a reliable pricing model that adapts to both location and structural variables

💡 Thanks for reviewing this project! We hope it offers valuable insights into how machine learning can enhance the real estate industry through smart price prediction.
