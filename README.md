# Multiple-Linear-Regression
📉 Multiple Linear Regression on Car Price Dataset
This project implements Multiple Linear Regression (MLR) to model and predict car prices based on multiple independent variables such as age, mileage, fuel type, and more.

🎯 Objective
To build a statistical model that can predict the price of a car using multiple features from the dataset. The aim is to understand the relationships between price and its influencing factors.

🧠 What is Multiple Linear Regression?
Multiple Linear Regression is a supervised learning algorithm used to predict the value of a dependent variable (target) based on two or more independent variables (predictors).

📁 Dataset Overview
Dataset: ToyotaCorolla - MLR.csv

Target Variable: Price

Features include:

Age_08_04 (Car age in months)

KM (Mileage)

Fuel_Type (Petrol, Diesel, CNG)

HP (Horsepower)

Automatic (Transmission)

and other relevant vehicle specs

🔍 Techniques and Process
1. Data Loading and Preprocessing
Loaded dataset using pandas.

Separated features (X) and target (y).

Encoded categorical variables like Fuel_Type into dummy variables for regression modeling.

2. Model Building
Used LinearRegression from sklearn.linear_model.

Fit the model on training data to learn the coefficients.

3. Model Evaluation
Evaluated model performance using:

R² Score: How well the model explains variability in the target.

Adjusted R²: Adjusts R² based on the number of predictors used.

RMSE (Root Mean Squared Error): Standard deviation of residuals.

📊 Why This Process?
MLR is suitable when multiple features are believed to influence the target.

Helps interpret the impact of each variable through model coefficients.

Allows for diagnostic checks like multicollinearity, residual analysis, and feature significance.

✅ Key Insights
Variables like car age and mileage showed significant negative correlation with price.

Categorical encoding allowed the model to handle non-numeric features effectively.

R² score indicated the model explains a substantial proportion of the variance in car prices.

🛠️ Libraries Used
pandas – for data manipulation

numpy – for numeric computation

scikit-learn – for modeling and evaluation
