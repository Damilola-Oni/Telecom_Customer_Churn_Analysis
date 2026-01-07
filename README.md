# Telecom Customer Churn Analysis

## Overview
This project presents an end-to-end analysis of customer churn in the telecommunications industry.
The objective is to identify key drivers of churn, evaluate churn risk using predictive modeling, and provide actionable business recommendations to improve customer retention.

## Business Problem
Customer churn is a critical challenge for telecom companies, directly impacting revenue and growth.
Understanding which customers are most likely to churn—and why—enables targeted retention strategies and more efficient resource allocation.

## Dataset
The dataset contains customer demographic information, subscription details, service usage patterns, payment behavior, and churn status.
It represents a realistic telecom customer base suitable for both analytical exploration and predictive modeling.

## Approach
The analysis follows a structured analytics workflow:

1. **Problem Framing** – Defining churn and its business impact  
2. **Data Cleaning & Preparation** – Handling data types, missing values, and validating the target variable  
3. **Exploratory Data Analysis (EDA)** – Identifying churn patterns across customer segments  
4. **Feature Engineering** – Creating engagement, tenure, and payment-related features  
5. **Churn Modeling** – Training a Logistic Regression model  
6. **Postdictive Analysis** – Evaluating model strengths, weaknesses, and trade-offs  
7. **Business Recommendations** – Translating insights into retention actions  

## Key Insights
- Churn is highest among newly acquired customers (0–3 months tenure)
- Month-to-month contract customers churn significantly more than long-term contract customers
- Higher monthly charges are associated with increased churn
- Customers with fewer subscribed services are more likely to churn
- Automatic payment methods are linked to lower churn rates

## Modeling Results
- **Model:** Logistic Regression  
- **ROC-AUC:** ~0.82  
- **Precision (Churn):** ~0.65  
- **Recall (Churn):** ~0.49  

The model performs well at identifying high-risk churn customers but misses some churners who do not exhibit strong observable signals.

## Business Recommendations
- Prioritize early-stage customer onboarding and engagement
- Incentivize long-term contracts for month-to-month customers
- Reinforce value for customers on higher-priced plans
- Reduce payment friction by encouraging automatic payment methods

## Tools & Technologies
- Python (pandas, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook
- Git & GitHub

> A Power BI executive dashboard is being developed as an extension of this analysis to translate insights into a stakeholder-facing decision tool.

