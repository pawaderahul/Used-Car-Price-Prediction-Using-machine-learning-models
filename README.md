# Used-Car-Price-Prediction-Using-machine-learning-models


## Problem Statement
    A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts.

    They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors. affectingthe pricing of cars in the American market, since those may be very different from the Chinese market. 
    The company wants to know:
    1. Which variables are significant in predicting the price of a car?
    2. How well those variables describe the price of a car?
    Based on various market surveys, the consulting firm has gathered a large data set of different types of cars across the America market.


## Business Goal
    We are required to model the price of cars with the available independent variables.It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
    
    
## Framing Problem:
     For now, we can categorize our Machine Learning System as:
         Supervised Learning Task- we are given labled training data
         Regression task- our model is expected to predict the price of Used Car using given features
         
         
## [Dataset](https://github.com/pawaderahul/Used-Car-Price-Prediction-Using-machine-learning-models/blob/main/CarPrice_Assignment.csv)

## [Data Dictionary](https://github.com/pawaderahul/Used-Car-Price-Prediction-Using-machine-learning-models/blob/main/Data%20Dictionary%20-%20carprices.xlsx)

## [Data Preprocessing](https://github.com/pawaderahul/Used-Car-Price-Prediction-Using-machine-learning-models/blob/main/Data_Preprocessing.ipynb)


## ML Models:
1. [Linear Regression](https://github.com/pawaderahul/Used-Car-Price-Prediction-Using-machine-learning-models/blob/main/Linear%20Regression.ipynb)
2. [XG Boost](https://github.com/pawaderahul/Used-Car-Price-Prediction-Using-machine-learning-models/blob/main/XGBoost.ipynb)
3. [Random Forest](https://github.com/pawaderahul/Used-Car-Price-Prediction-Using-machine-learning-models/blob/main/Random_Forest.ipynb)


## Model Performance (According to r2_score value)
| Models             | Accuracy Score       | 
| ------------------ |:--------------------:|   
| Linear Regression  | 0.8730               |
| Random Forest      | 0.9152               |
| XGBoost            | 0.9142               |


## Hence Random Forest model gives best performance for our data
