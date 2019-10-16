# Price-Prediction-for-AirBnB-listings

This project analyzes AirBnB listing dataset, which has 37 features and log price of that particular listing as output. The dataset contains 74,112 records from which 80% data is used for training of different models, while 20% test data is used for evaluation of that model. 


## Dataset 

https://www.kaggle.com/stevezhenghp/airbnb-price-prediction

## Exploratory Data Analysis 

* Removal of unnecessary features(URLS, thumbnails)
* Feature reduction using Principal Component Analysis
* Correlation analysis between features and output using corr plots
* Label encoding on data (Categorical to Numerical)
* Forward Feature Selection
* LASSO 
* Recursive Feature Elimination
* Tests to find linear relation between features using QQ Plots
* Multivariate Normality test and Homoscedasticity Test

## Prediction Models
* Linear Regression with cross validation
* Logistic Regression
* Stepwise Regression


## Evaluation metrics
* AIC,BIC
* R^2

## Requirements

* sklearn
* keras
* matplotlib
* tensorflow
* numpy
* pandas
