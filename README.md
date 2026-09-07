# EX-NO.-4a-MACHINE-LEARNING-MODEL-LINEAR-REGRESSION
## AIM
To predict house prices using regression models and compare the performance of different machine learning regression models based on RMSE, MAE, and R².
1.Machine Learning:Machine Learning is used to learn patterns from existing data and make predictions. 
•	Regression is a supervised learning technique used to predict continuous numerical values. 
•	In this experiment, regression models are used to predict the price of a house. 
•	The dataset contains house-related features such as: 
o	square_feet 
o	num_rooms 
o	age 
o	distance_to_city(km) 
•	The target variable is: 
o	price 
# THEORY 
1. Introduction
Linear Regression is a supervised machine learning algorithm used to predict a continuous
numerical value based on one or more input variables.
It assumes that there is a linear relationship between the input variable(s) and the output
variable.
For example, Linear Regression can be used to predict:
House prices based on area Salary based on years of experience Sales based on advertising
expenditure Temperature based on environmental factors Student marks based on study hours
2. Types of Linear Regression Simple Linear Regression
Simple Linear Regression uses one independent variable to predict one dependent variable.
The equation is:
y = b₀ + b₁x
where:
y = predicted output x = input variable b₀ = intercept b₁ = slope/coefficient
Multiple Linear Regression
Multiple Linear Regression uses two or more independent variables to predict the dependent
variable.
The general equation is:
y = b₀ + b₁x₁ + b₂x₂ + ... + bₙx
# WORKING PRINCIPLE 
The Linear Regression algorithm attempts to find the best-fit straight line through the available
data points.
The best-fit line is selected by minimizing the difference between the actual values and the
predicted values.
These differences are called residuals or errors.
The model commonly uses the Least Squares Method, which minimizes the sum of squared
errors.
The process can be represented as
             ┌──────────────────────┐
             │   House Price Dataset │
             └──────────┬───────────┘
                        ↓
             ┌──────────────────────┐
             │   Data Preprocessing │
             │ • Handle missing data│
             │ • Select features     │
             │ • Scale data          │
             └──────────┬───────────┘
                        ↓
             ┌──────────────────────┐
             │  Feature Selection   │
             │ • Square Feet         │
             │ • Number of Rooms     │
             │ • Age                 │
             │ • Distance to City    │
             └──────────┬───────────┘
                        ↓
             ┌──────────────────────┐
             │ Train-Test Split     │
             └──────────┬───────────┘
                        ↓
        ┌───────────────┴────────────────┐
        ↓                                ↓
┌─────────────────┐              ┌─────────────────┐
│ Regression      │              │ Regression      │
│ Model 1         │              │ Model 2, 3...   │
└────────┬────────┘              └────────┬────────┘
         └───────────────┬────────────────┘
                         ↓
              ┌──────────────────────┐
              │  House Price         │
              │  Prediction          │
              └──────────┬───────────┘
                         ↓
              ┌──────────────────────┐
              │ Model Evaluation     │
              │ • RMSE               │
              │ • MAE                │
              │ • R²                 │
              └──────────┬───────────┘
                         ↓
              ┌──────────────────────┐
              │ Compare Models &     │
              │ Select Best Model    │
              └──────────────────────┘
## DATASET DESCRIPTION
•	Dataset: House Price Dataset 
•	Problem: Predict house price. 
•	Features (X): 
o	square_feet – size of the house. 
o	num_rooms – number of rooms. 
o	age – age of the house in years. 
o	distance_to_city(km) – distance from the city centre. 
•	Target (y): 
o	price – continuous house price. 
## PROBLEM STATEMENT
•	Develop a machine learning model to predict house prices. 
•	Use house characteristics as input. 
•	Train different regression models. 
•	Compare their prediction performance. 
•	Select the better-performing model based on evaluation metrics. 
## REGRESSION MODELS USED
The uploaded notebook compares the following models:
1.	Linear Regression 
2.	Ridge Regression 
3.	Lasso Regression 
4.	ElasticNet Regression 
5.	Polynomial Regression 
6.	Decision Tree Regressor 
7.	Random Forest Regressor 
8.	Gradient Boosting Regressor 
9.	Support Vector Regressor (SVR) 
10.	K-Nearest Neighbors (KNN) Regressor 

# COLAB LINK
https://colab.research.google.com/drive/1Vszxt_Kk15eEIoMNZyvfMT2Ckvm5WY5s
## CONCLUSION
Thus, Linear Regression and other regression models were successfully applied for house price prediction, and their performance was compared using standard regression evaluation metrics.

