# Car Price Prediction Project

## Overview
This project aims to build a predictive model to estimate car prices in the American market based on several car features such as brand, engine type, model year, and more. The dataset used contains various independent variables that influence the car price, and we apply multiple regression models to predict the car price accurately.

## Key Features:
- **Data Preprocessing**: Missing values are imputed, categorical variables are encoded, and features are scaled for model compatibility.
- **Regression Models**: We implement five regression algorithms to compare their performance in predicting car prices.
  1. **Linear Regression**
  2. **Decision Tree Regressor**
  3. **Random Forest Regressor**
  4. **Gradient Boosting Regressor**
  5. **Support Vector Regressor**
- **Model Evaluation**: Models are evaluated based on R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
- **Feature Importance Analysis**: The Random Forest model is used to analyze the significance of each feature.
- **Hyperparameter Tuning**: The Random Forest model is fine-tuned using GridSearchCV to improve its performance.

## Dataset
The dataset used for this project is available [here](https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link). It contains various features of cars in the American market, including brand, model, engine, mileage, etc.

## Installation
To run this project, you need the following libraries:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install them via pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
