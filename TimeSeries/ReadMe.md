# Taxi Orders Forecasting  

## Project Status  
The project is fully completed. Finished.  

## Data  

- Number of taxi orders  

## Objective  

**Client:** "Chyotenkoye Taxi" Company  

**Goal:** Attract more drivers during peak demand periods.  

**Task:** Build a model to predict the number of taxi orders for the next hour.  

## Conclusions  

Several models were considered during the project.  
The gradient boosting model *LGBMRegressor* performed best on the validation dataset when more features were included.  
The data was split sequentially into validation and test datasets, with the test dataset representing the final portion of the time series.  
As a result, the model showed worse RMSE on the test dataset than on the validation dataset. Additionally, the graph of the time-series moving average of taxi orders at the end trends upward, making it a less stationary time series compared to earlier data.  

## Libraries Used  

*Pandas*  
*Sklearn*  
*statsmodels*  
*Lightgbm*  
*Matplotlib*  

## Models Used  

*LGBMRegressor*  
*LinearRegression*  
*RandomForestClassifier*  
