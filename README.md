# 🚗 BMW Price Prediction using Machine Learning

A Machine Learning project that predicts BMW car prices based on multiple vehicle features using Python and regression models.
The project applies data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning algorithms to build an accurate price prediction model.

This project demonstrates practical data science and predictive analytics skills including data cleaning, visualization, and model evaluation.

## Project Overview

Car price prediction is an important application in the automobile industry and resale markets. This project analyzes BMW vehicle data and builds a machine learning model to estimate the expected price of a car based on its specifications.

The workflow includes:

Data Collection

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Feature Engineering

Model Training

Model Evaluation

Price Prediction

## Dataset

The dataset contains information about BMW vehicles including:

Feature	Description
Model	BMW car model
Year	Manufacturing year
Mileage	Distance driven
Engine Size	Engine capacity
Fuel Type	Petrol / Diesel
Transmission	Manual / Automatic
Price	Target variable (car price)

Dataset used:
bmw_global_sales_2018_2025.csv

## Technologies Used

Python

Pandas – Data manipulation

NumPy – Numerical computation

Matplotlib – Data visualization

Seaborn – Statistical visualization

Scikit-learn – Machine learning models

## Exploratory Data Analysis

EDA was performed to understand relationships between variables and identify patterns affecting car prices.

Key analyses include:

Price distribution

Mileage vs Price relationship

Model wise price comparison

Correlation heatmap

Feature importance analysis

These insights help identify the most influential factors affecting car prices.

## Machine Learning Model

The project uses Supervised Learning Regression Models to predict car prices.

Typical workflow:

Data preprocessing

Encoding categorical variables

Train-test split

Model training

Model evaluation

Example code:

from sklearn.model_selection import train_test_split

X = df.drop('price', axis=1)
y = df['price']

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2, random_state=42
)

## Model Evaluation

The model performance is evaluated using standard regression metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

These metrics help determine how accurately the model predicts BMW prices.

## Key Insights

Vehicle year and mileage strongly influence price

Certain BMW models have significantly higher resale value

Engine size and fuel type impact price variations

## Future Improvements

Deploy model using Streamlit web app

Add multiple regression models for comparison

Perform hyperparameter tuning

Use larger automobile datasets
