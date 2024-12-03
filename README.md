# Housing-price-prediction

### Table of Content

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Predictive Analysis](#predictive-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)


### Project Overview

This data analysis aims to identify the most important features impacting housing price and improve price preciction. By analyzing how various factors influence housing price, we seek to predict future housing price, and make data-driven recommendations.


### Data Sources

Housing price prediction data: The primary dataset used for this analysis is the "Housing.csv" file, containing detailed information aboutkey features for predicting housing price.


### Tools

-Excel


### Data Cleaning

In the initial data preparation phase, we performed the following tasks:
1.	Converting Data Types: Ensured fields are in the correct data type, such as converting columns with numbers to integer or float.
2.	Check and Removal of duplicates: 5 duplicates were found and removed
3.	Correcting Inconsistent Data: Standardize spellings of word on the product and sales pipeline table and other fields to ensure consistency.
4.	Ensuring Data Integrity: To guarantee the accuracy and reliability of our data, validation on the relationships between tables and rectify data inconsistencies was done.

### Exploratory Data Analysis

EDA involved exploring this data to answer questions, such as:
- What are the averaging prices of houses based on furnishing status?
- What is the relationship between factors (except furnishing status) with price?
- Visualize each relationship with a scatterplot chart and create a dashboard with all charts?


### Predictive Analysis

Predictive analysis involved exploring data to answer questions such as:
- Create a model using the factors with medium and high correlation with price (0.3 - 1 ) to predict price.
- Create another model using all the factos in the dataset to predict price, compare the prediction accuracy to the first model.
- What factors are the strongest predictors of housing prices?
- How accurately can the model predict housing price?


### Data Analysis

Data Anaylsis tool pack (Regression).


### Results

The analysis results are summarized as follows:
1. Forcasted prices for model 1 accounts for 63% of housing price and model 2 accounts for 66% of housing price.
2. Model 2 has a negative intercept for price.


### Recommendations

- Incorporate additional variables to further forcast housing price.
- Consider area and number of bedrooms when evaluating housing prices.
