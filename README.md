# data_mid_bootcamp_project_classification
In this project, I built a classification model to predit customer decision for a bank whether they decide to take the offer to accept the cradit offer. 

I have splited the whole project into 5 parts: 
## EDA (Overview + In depth)
In this part, I have done EDA in an overview and in-depth level. 

* Overall level:
I am  looking at the whole dataset. Here are some finding: 
The dataset has 17 columns in total, with 18000 entries. It has only 24 rows which included null data. 

Here are the summary of the features: 3 columns
Discrete Numerical Data:
    - Bank Account Open
    - Credit Card Held
    - Home Owned
Continous Numercial Data: - 5 columns
    - Balance (Average and for each quarter) 
Categorical Data: - 6 columns
    - Offer Accepted (Target)
    - Reward 
    - Income Level
    - Overdraft Protection 
    - Credit Rating
    - Own your Home

* In-depth level: 
In this level, I paid deep attention to each feature itself: 
1. Correlation: There is a high correlation between the average balance and each quarter. 
2. The only Continous Numerical feature is not normally distrubuted. 
3. The target feature is high imbalanced. 

This step is very crucial as it helps me to understand how I should clean and process my data for a classification model. 

## Cleaning (General + Numerical + Categorical)
* Genereal: clean null value, unwanted feature (customer_ID), columns_name
* Numerical cleaning: 
Continous numberical: clean outlairs

## Data Featuring (Numerical + Categorical)
* Categorical featuring: transform categorical data to discreate numerical data, such as: Income Level, Credit Rating 
* Numerical cleaning: Scale 

## Modeling
  M1: the base model without any cleaning, featuring
  M2: clean the outliars based on Average Income feature
  M3: Deal with inbalanced data
  M3_1: SMOTE, oversampling + scaling numberical
  M4: choosing features only base on coefficient score
  M5: choosing features base on my understanding
## Modeling Validation
The 
## Reporting
