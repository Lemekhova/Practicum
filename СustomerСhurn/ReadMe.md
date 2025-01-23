# Customer Churn  

## Project Status  
The project is fully completed. Finished.  

## Data  

We were provided with historical data on customer behavior and contract terminations with the bank.  

Features:  

- row index in the data  
- unique client ID  
- last name  
- credit rating  
- country of residence  
- gender  
- age  
- number of years the client has been with the bank  
- account balance  
- number of bank products used by the client  
- presence of a credit card  
- client activity  
- estimated salary  

Target Feature:  

- client churn (whether the client left the bank)  

## Objective  

**Client:** "Beta-Bank"  

Clients started leaving the bank every month. Bank marketers calculated that retaining current clients is cheaper than acquiring new ones.  

The goal is to predict whether a client will leave the bank soon or not.  

## Conclusions  
Three classification models were evaluated: Decision Tree, Linear Regression, and Random Forest. The most suitable parameters were selected to achieve maximum accuracy.  

By balancing the dataset with different methods, it was determined that the Random Forest classification model, balanced by undersampling, gives the most accurate result that meets the task requirements.  

## Libraries Used  
*Pandas*  
*Sklearn*  
*Numpy*  

## Models Used  
*DecisionTreeClassifier*  
*LogisticRegression*  
*RandomForestClassifier*  
