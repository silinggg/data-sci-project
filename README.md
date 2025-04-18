# Predicting Hotel Booking Cancellations through Data Science

> Lab Group: ECDS Team 11
> Team Members: Madhumita, Onaya, Si Ling

---
## About

The SC1015 Data Science Mini Project focuses on predicting hotel booking cancellations by building predictive models based on a real-world dataset from a Portuguese hotel chain.

Follow our project step-by-step, and explore these notebooks in the following order:

1. #data-cleaning-and-preprocessing
2. #exploratory-data-analysis-eda
3. #feature-selection
4. #model-building
5. #model-evaluation-and-final-insights

## Problem Statement

**Practical Motivation:**
In the hospitality industry, booking cancellations are unavoidable and bound to happen for various reasons, which can cause significant operational and financial disruptions to hotels. They face challenges such as inefficient room allocations and loss of potential revenue opportunities. If, however, hotels could predict cancellations in advance (via data science), more proactive measures like pricing strategies, intelligently overbooking could be implemented for their benefit.

**Problem Definition:**
Are we then able to predict hotel booking cancellations using machine learning based on selected customer and reservation attributes, and which model would predict it the best?

## Dataset Used
Kaggle hotel booking dataset with over 100000 samples. It contains features such as lead time, agent, customer type, deposit type, country, and more.

---

## Data Preparation

We performed the following data cleaning steps:
- Dropped missing values/imputed where necessary
- Dropped irrelevant columns (e.g., booking ID, reservation status date)
- Encoded categorical variables
- Handled class imbalance using class weights
- Selected the top 5 features based on correlation to satisfy the variable constraints

---

## Exploratory Data Analysis (EDA)

For EDA and data visualisations of relevant features, We used:
- Heatmaps
- Histograms
- box plots
- Correlation matrices

---

## Machine Learning Approach

**Model Used:**  
We implemented and evaluated the following models:
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier (optional)

##Conclusion  
> Given the dataset and models built, it is possible to predict hotel booking cancellations with relatively high accuracy
> The best performing model was: `XGBoost Classifier` with the highest accuracy (above 80%), recall, and f1 score

## Learning Beyond the Course: 
- Handling class imbalance to reduce bias to the majority class `class_weight='balanced'`
- Encoding categorical variables
- Using Cramer's to find the correlation of categorical variables
- Data visualisation via choropleth map and pie charts
- Implement RandomForestClassifier beyond just what we learnt in theory
- Explored `XGBoost` for optimisation
---

## Contributors

