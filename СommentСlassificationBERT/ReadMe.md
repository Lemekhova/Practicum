# Project for "Wikishop" with BERT  

## Project Status  
The project is fully completed. Finished.  

## Data  

A labeled dataset indicating toxicity:  

- **text** — contains the comment text  
- **toxic** — target label  

## Objective  

**Client:** Online store "Wikishop"  

**Goal:** Develop a tool to detect toxic comments and flag them for moderation.  

**Task:** Train a model to classify comments as positive or negative.  

The model must achieve an F1 score of at least 0.75.  

## Conclusions  

To predict the toxicity of comments, models such as Logistic Regression, Decision Tree, and Random Forest were evaluated.  

The text was preprocessed through lemmatization and cleaning, then vectorized and preprocessed using the BERT model. Training was performed both before and after applying BERT.  

It is worth noting that preprocessing with BERT and subsequent predictions were conducted on a subset of the data due to the time required to generate embeddings on the full dataset with the available computational resources. For this reason, the quality of models with BERT was evaluated using a sample of 1,000 entries (embedding generation took 42 minutes).  

Models trained after feature preparation with BERT learned significantly faster. However, their F1 scores were notably lower, likely due to the incomplete dataset used for BERT preprocessing.  

## Libraries Used  

*Pandas*  
*Nltk*  
*Numpy*  
*Re*  
*Torch*  
*Transformers*  

## Models Used  

*BERT*  
*LogisticRegression*  
*DecisionTreeClassifier*  
*RandomForestClassifier*  
