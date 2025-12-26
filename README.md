# Customer Churn Analysis


## Goal: Identify churn patterns and evaluate baseline prediction models using a telecom customer dataset.

---

## Overview

This project analyzes customer churn to understand which customer behaviors and service characteristics are most strongly associated with attrition. The focus is on extracting actionable insights through exploratory analysis and evaluating simple predictive models for churn risk.

---

## Problem Statement

Customer churn directly impacts revenue and customer lifetime value. The objective of this project is to identify high-risk customer segments and highlight key factors that can inform practical, data-driven retention strategies.

---

## Project Workflow

- Cleaned and prepared the dataset for analysis  

- Performed exploratory data analysis to compare churned vs retained customers  

- Analyzed churn behavior across contract type, tenure, and monthly charges  

- Built churn prediction models using Logistic Regression, Random Forest, and LightGBM  

- Evaluated models using ROC and Precision-Recall curves  

---

## Key Insights

- Month-to-month contracts show the highest churn risk  

- Customers with higher monthly charges churn more frequently  

- New customers are more likely to churn than long-tenure customers  

- Customers using additional services tend to have lower churn  

- LightGBM showed better churn separation compared to baseline logistic regression, particularly for high-charge customers.

---

## Tools & Technologies

- Python  

- Pandas, NumPy  

- Matplotlib, Seaborn  

- Scikit-learn  

- Jupyter Notebook  

---

## Deliverables

- Exploratory Data Analysis notebook  

- Churn prediction models with evaluation metrics  

- Visual insights highlighting key churn drivers  

---

## How to View

- Open `churn.html` for the full analysis  

- Or run `churn.ipynb` in Jupyter Notebook  
