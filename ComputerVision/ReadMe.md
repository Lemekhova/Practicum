# Predicting Final Properties of New Materials (Composite Materials). Selecting the Best Model.

## Project Status  
The project is fully completed. Finished.

## Data  

The dataset contains information about the initial properties of composite material components (amount of binder, filler, curing temperature, etc.).

## Objective  

**Goal:** Predict the final properties of composite materials.  
**Task:** Select the best model for determining the final properties of composite materials.

## Conclusions  

To predict five characteristics of the composite material based on its components and formation methods, four models were evaluated: Linear Regression, Random Forest, Gradient Boosting, and a Neural Network.

Among the models, the Neural Network showed the highest accuracy. However, due to the dataset size, it performed inconsistently and didn’t always provide reliable predictions.

The second most accurate model was Linear Regression. Moreover, during testing, the Linear Regression model consistently outperformed the Neural Network in accuracy.

Based on these findings, it is recommended to use the Linear Regression model for further work.

## Libraries Used  

*Pandas*  
*Keras*  
*LightGBM*  
*Matplotlib*  
*Sklearn*  

## Models Used  

*LinearRegression*  
*RandomForestRegressor*  
*LGBMRegressor*  
*Sequential*  
