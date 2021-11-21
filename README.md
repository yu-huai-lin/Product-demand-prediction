# Product-demand-prediction - Yu-Huai Lin
### Predicting Product Sales Demand

### General Info
This project contains datasets and a notebook that aims to analyse and model the historical product data in order to predict sales demand. Overall, the process includes data extraction and transformation, exploratory analysis, feature engineerng, model training and evaludation, and tuning.

### Requirements

python version 3.6

#### Libraries
Package             Version
------------------- ---------
numpy               1.21.2

packaging           21.0

pandas              1.3.2

plotly              5.2.1

scikit-learn        0.24.2

scipy               1.7.1

seaborn             0.11.2

sklearn             0.0

statsmodels         0.12.2

matplotlib          3.4.3

### Instructions
To run the solution.ipynb script, you need to meet the above requirements and import the modules and libraries used in the notebook. 

### Files
solution.ipynb
this file contains the analysis and model building

historical product popularity.csv
this file contains information about product searches and popularity 

historical unit sales.csv
this file contains the target variable, which is the number of product unit sold in the past

product articels attributes.csv
This file contains most of the categorical attributes of products. 

### Exploratory Data Analysis

| Feature Type | Columns|
|:----|:-----------|
| # Categorical | Boxplot, Countplot|
| # Numerical| Histogram, Correlation|

### Data Transformation

| Columns| Method|
|:----|:-----------|
| #Categorical | Target Encoding due to high cardinality|
| #Numerical| Mix-max scaling |

### Modelling

| Models | Method|
|:----|:-----------|
| #MVP | Mean Imputation (Encoding)|
| #Baseline Model| Multiple Linear Regression |
| #Advance Model| Random Forest Regressor |

### Feature Importance

| Models | Method|
|:----|:-----------|
| #Linear Regression| Coefficient and p-value |
| #Random Forest| Built-in Feature Importance |

### Outcome

| Models |MAE|MSE|RMSE|MAPE|
|:----|:---|:---|:---|:---|
| #MVP | |
| #Linear Regression| |
| #Random Forest|  |


