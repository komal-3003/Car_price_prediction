# Car Price Prediction using Linear Regression
## Project Objective
The objective of this project is to build a predictive model that estimates the price of cars based on various features such as brand, mileage, fuel type, and engine specifications. The goal is to help businesses and individuals make informed pricing decisions using data-driven insights.

## Project Description
- This project focuses on predicting car prices using a Linear Regression model trained on a real-world dataset from Kaggle.
- It involves data preprocessing, exploratory data analysis (EDA), feature engineering, and model evaluation.
- The model identifies key factors influencing car prices and provides a reliable estimate based on input features.

## Key Performance Indicators (KPIs)
- Car Brand / Company
- Year of Manufacture
- Fuel Type
- Transmission Type
- Mileage (km driven)
- Engine Capacity
- Selling Price (Target Variable)

## Dataset used
- <a href="/kaggle/input/datasets/adhurimquku/ford-car-price-prediction/ford.csv">Dataset</a>
## Project Process
## 1️.Data Collection
- The dataset was sourced from Kaggle and includes structured data related to used cars.
- It contains both categorical and numerical features influencing car prices.
  
## 2.Data Cleaning & Preparation
- Handled missing and null values
- Removed duplicate records
- Converted categorical variables using encoding techniques
- Checked and corrected data types
- Applied Standard Scaling to normalize numerical features

## 3.Exploratory Data Analysis
- Visualized relationships between features and price
- Identified trends based on fuel type, transmission, and car age
- Analyzed distribution of numerical variables
- Detected outliers and data patterns
  
## 4️.Feature Engineering & Correlation Analysis
- Performed correlation analysis to identify strong predictors
- Removed irrelevant or low-impact features
- Selected important variables for model training

## 5.Model Development
-Implemented Linear Regression algorithm
- Split data into training and testing sets
- Trained the model on scaled data

## 6.Model Evaluation
- Evaluated model performance using R² Score (Coefficient of Determination)
- Measured how well the model explains variance in car prices
- Achieved a reliable prediction accuracy indicating good model performance

## Project Insights
-Car price is strongly influenced by brand, engine capacity, and year of manufacture
- Newer cars tend to have higher resale value
- Fuel type and transmission also play a significant role in pricing
- Mileage negatively impacts the selling price

## Conclusion
This project demonstrates how machine learning can be used to predict car prices effectively. The Linear Regression model provides a simple yet powerful approach for understanding price trends and making accurate predictions. With further optimization and advanced models, prediction accuracy can be improved even more.

## Future Scope
- Apply advanced models like Random Forest or XGBoost
- Perform hyperparameter tuning
- Deploy the model using Flask/Streamlit
- Integrate real-time user input for predictions
