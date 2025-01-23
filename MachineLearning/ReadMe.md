# Selecting a Location for a Well  

## Project Status  
The project is fully completed. Finished.  

## Data  

Geological exploration data for three regions:  

- Unique well identifier  
- Three feature values for each point (their exact meanings are irrelevant, but the features themselves are significant)  
- Volume of reserves in the well (thousands of barrels)  

## Objective  

**Client:** Oil extraction company "GlavRosGosNeft."  

**Initial Data:** Oil samples from three regions, each containing 10,000 oil fields where the quality and reserves of oil were measured.  

**Goal:** Determine where to drill a new well.  

**Task:** Build a machine learning model to identify the region where extraction will yield the highest profit. Analyze potential profit and risks using the *Bootstrap* technique.  

## Conclusions  

Three regions of oil wells were analyzed. Based on the actual production volume data, models were trained to predict oil production. Using predictions, 200 of the most productive wells were selected from 500 randomly chosen wells in each region. The actual revenues from these 200 wells were then estimated. The analysis led to conclusions regarding the profitability of each region.  

## Libraries Used  

*Pandas*  
*Sklearn*  
*Numpy*  

## Techniques Used  

*Bootstrap*  
