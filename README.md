# customer-churn-model-prediction
model building
Telecom Customer Churn Prediction

This project focuses on predicting customer churn for a telecom company to help identify customers likely to leave and understand factors driving churn.

## Dataset & Features

- Customer demographics and account info
- Service details: payment method, monthly charges, contract type
- Add-ons like online security and device protection

## Workflow

1. *Data Cleaning:* Dropped very few missing values; no duplicates found.
2. *Exploratory Data Analysis:* Used CountPlots and BoxPlots to explore feature distributions and their relation to churn.
3. *Feature Selection:* Applied chi-square tests to identify significant categorical features.
4. *Modeling:*  
   - Split data into train/test sets.  
   - Built Decision Tree (73% accuracy) and Random Forest (86% accuracy) models.  
   - Tuned Random Forest hyperparameters using RandomizedSearchCV, improving accuracy to ~80%.

## Key Insights

- Customers with *month-to-month contracts, **high monthly charges, and **no online security* are more likely to churn.
- These insights can help design targeted retention strategies.

## Skills Developed

- Data preprocessing and cleaning
- Statistical feature selection
- Model building and tuning
- Extracting actionable business insights
