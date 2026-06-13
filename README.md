# customer-churn-analysis
# Customer Segmentation & Retention Analysis

## Problem Statement
Telecom company ke customers churn kar rahe hain. 
Is project me customers ko segment kiya aur churn predict kiya.

## Dataset
- IBM Telco Customer Churn Dataset
- 7,043 customers, 21 features
- Source: Kaggle

## Project Structure
- Phase 1 → EDA
- Phase 2 → Feature Engineering  
- Phase 3 → KMeans Clustering (3 segments)
- Phase 4 → Churn Prediction (XGBoost - ROC AUC: 0.85)
- Phase 5 → Retention Analysis & CLV
- Phase 6 → Power BI Dashboard

## Key Findings
- Month-to-month customers churn at 43%
- First 12 months is critical retention window
- Fiber optic users churn more despite premium pricing
- XGBoost best model with ROC-AUC of 0.85

## Tech Stack
Python, Pandas, Scikit-learn, XGBoost, SHAP, Power BI

## How to Run
1. Clone this repo
2. Install requirements → pip install -r requirements.txt
3. Run notebooks in order Phase1 → Phase6
