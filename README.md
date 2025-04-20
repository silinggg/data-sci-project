# Predicting Hotel Booking Cancellations through Data Science

> Lab Group: ECDS Team 11
> Team Members: Madhumita, Onaya, Si Ling

---
## About

The SC1015 Data Science Mini Project focuses on predicting hotel booking cancellations by building predictive models based on a real-world dataset from a Portuguese hotel chain.

Follow our project step-by-step, and explore these notebooks in the following order:

1. [Data Cleaning](1_Data_Cleaning.ipynb)
2. [Exploratory Data Analysis](2_exploratory%20data%20analysis.ipynb)
3. [Decision Tree](3_Decision_Tree.ipynb)
4. [Random Forest](4_Random%20Forrest.ipynb)
5. [XGBoost](5_XG%20Boost.ipynb)

## Problem Statement

**Practical Motivation:**
In the hospitality industry, booking cancellations are unavoidable and bound to happen for various reasons, which can cause significant operational and financial disruptions to hotels. They face challenges such as inefficient room allocations and loss of potential revenue opportunities. If, however, hotels could predict cancellations in advance (via data science), more proactive measures like pricing strategies, intelligently overbooking could be implemented for their benefit.

**Problem Definition:**
Are we then able to predict hotel booking cancellations using machine learning based on selected customer and reservation attributes, and which model would predict it the best?

## Dataset Used
Kaggle hotel booking dataset with over 100000 samples. It contains features such as lead time, agent, customer type, deposit type, country, and more.

---

## Data Preparation and Cleaning

We performed the following data cleaning steps:
- Dropped rows with null values/imputed where necessary
- Dropped irrelevant columns (e.g., arrival date year, reservation status date)
- Checked for class imbalance and handled it using class weights
- Transformed the features "company” and “agent” to string type to treat it as categorical variables
- Added new features such as "stay duration”’ and “total guests”
- Removed outliers under certain features
- Encoded categorical variables using One-hot encoding
- Selected the top 5 features based on correlation to satisfy the variable constraints

---

## Exploratory Data Analysis (EDA)

For EDA and data visualisations of relevant features, We used:
- Heatmaps
- Histograms
- Box plots
- Correlation matrices
- Pie charts
- Choropleth map

---

## Machine Learning Approach

**Model Used:**  
We implemented and evaluated the following models:
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

##Conclusion 

Given the dataset and models built, it is possible to predict hotel booking cancellations with relatively high accuracy
The best performing model was: `XGBoost Classifier` with the highest accuracy (above 80%), recall, and f1 score

## Learning Beyond the Course: 
- Handling class imbalance to reduce bias to the majority class `class_weight='balanced'`
- Encoding categorical variables
- Using Cramer's V to find the correlation of categorical variables
- Data visualisation via choropleth map and pie charts
- Implement `RandomForestClassifier` beyond just what we learnt in theory
- Explored `XGBoost` for optimisation
---

## Contributors

