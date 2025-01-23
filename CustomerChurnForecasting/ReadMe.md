# Customer Churn Prediction for the Telecommunications Provider "NoDropCalls.com"

## Project Status  
The project is fully completed. Finished.

## Data  

- **Contract Information**  
  - Start date of service  
  - End date of service  
  - Type of contract (monthly payment, 1-year plan, 2-year plan)  
  - Electronic billing  
  - Payment method  
  - Monthly service cost  
  - Total service cost  

- **Customer Personal Data**  
  - Gender  
  - Senior citizen status  
  - Presence of a spouse  
  - Dependents  

- **Internet Service Information**  
  - Internet service  
  - Blocking unsafe websites  
  - Cloud file backup  
  - Antivirus  
  - Dedicated technical support line  
  - Streaming TV  
  - Movie catalog  

- **Telephony Service Information**  
  - Availability of parallel call lines  

## Objective  

**Client:** Telecommunications provider "NoDropCalls.com."  

**Goal:** Identify potential customers likely to churn. If a customer is identified as planning to leave, they will be offered promo codes and special conditions. The telecom provider's team has collected personal data, tariff details, and contract information for some of their customers.  

**Task:** Build a churn prediction model to identify customers who are likely to leave.  

## Conclusions  

Data analysis revealed that customer churn only began four months ago (since October 2019). A correlation was identified between the monthly payment amount and a customer’s likelihood of terminating their contract. The duration of service was also found to be a significant factor during further modeling.  

Only part of the initial dataset was used for training the models, and a new feature—customer service duration—was introduced.  

Four models were evaluated, with the Gradient Boosting model (*LGBMClassifier*) delivering the most accurate results.  

**Recommendation:** The company should review its monthly pricing structure to improve customer retention. Additionally, analyze any changes to tariffs or company policies starting from September 2019, if applicable, or identify external factors that may have contributed to customer churn beginning in October 2019.  

## Libraries Used  

*Pandas*  
*Sklearn*  
*Seaborn*  
*LightGBM*  
*Matplotlib*  
*Numpy*  

## Models Used  

*LogisticRegression*  
*RandomForestClassifier*  
*CatBoostClassifier*  
*LGBMClassifier*  
