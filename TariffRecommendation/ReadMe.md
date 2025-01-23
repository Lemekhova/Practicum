# Tariff Recommendation  

## Project Status  
The project is fully completed. Finished.  

## Data  

The initial data includes customer behavior data for those who switched to new tariffs.  

Each entry in the dataset represents information about one user's behavior over a month:  

- Number of calls,  
- Total call duration in minutes,  
- Number of SMS messages,  
- Internet usage in MB,  
- Tariff used during the month ("Ultra" — 1, "Smart" — 0).  

## Objective  

**Client:** Mobile operator "Megaline."  

**Goal:** Develop a system capable of analyzing customer behavior and recommending a suitable tariff: "Smart" or "Ultra."  

**Task:** Build a classification model to select the appropriate tariff. The model should achieve an accuracy score of at least 0.75. Verify the accuracy on the test dataset.  

## Conclusions  

The analysis revealed a correlation between the number of calls and the total call duration. During the modeling phase, several models were evaluated. Among them, the Random Forest classification model demonstrated the best performance, achieving an accuracy score of 0.81 on the test dataset.  

## Libraries Used  

*Pandas*  
*Matplotlib*  
*Sklearn*  
