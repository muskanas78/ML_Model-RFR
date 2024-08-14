# House Price Prediction
## Overview
This project involves predicting house prices based on selected features, within the dataset, using machine learning techniques. The objective is to build a reliable model that can estimate house prices based on these features.

## Features and Model
The features used for prediction include:
  1. Lot Area: The size of the property in square feet.
  2. BedroomAbvGr: The number of bedrooms above ground level.
  3. TBath: The total number of bathrooms, calculated by summing FullBath and HalfBath.

A Linear Regression model with polynomial features was implemented to capture nonlinear relationships between the features and the sale price. The model was trained and tested using cross-validation to ensure its robustness.

## Results
The model achieved a mean cross-validation score of approximately 0.37, indicating moderate performance. This outcome was anticipated given the use of only three features in the model. Predictions were made for new data points, with the estimated house price for a property with a lot area of 1500 square feet, 2 bedrooms, and 1 bathroom being approximately $105,253.96.
