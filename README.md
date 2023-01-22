# Project Name
Australian House Price Prediction 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
    - A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
- What is the business probem that your project is trying to solve?
    - The company wants to know:
        - Which variables are significant in predicting the price of a house, and
        - How well those variables describe the price of a house.
- What is the dataset that is being used?
    - The company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Based on EDA and modeling, the Lasso model with alpha (0.001) has selected for our predictions. The following are the top 5 predictors:
- GrLivAreaLog
- RoofMatl_ClyTile
- 1stFlrSFLog
- MSZoning_C (all)
- 2ndFlrSF


## Technologies Used
- pandas - version 1.5.0
- numpy - version 1.21.0
- seaborn - version 0.12.0
- sklearn - version 1.1.2


## Contact
Created by [@krishnajiraoh] - feel free to contact me!