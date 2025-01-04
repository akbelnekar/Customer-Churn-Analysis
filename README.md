# Customer-Churn-Analysis

## Project Overview

This project analyzes customer churn in a telecommunications company using PySpark. The goal is to identify key factors influencing customer churn and provide actionable insights to improve customer retention strategies.

## Key Findings

- Higher monthly charges and shorter tenure are significant predictors of churn.
- The source of customer acquisition influences churn rates (e.g., merchant collaborations had higher churn).
- Family member referrals are the most common source of new customers.

## Data Description

- Dataset: 'Telco_customer_churn.csv' and 'Telco_customer_churn_status.csv' 
- Source: IBM accelerator catalog
- ~7000 observations, 44 variables
- Includes customer demographics, services, billing info, churn status

## Methodology

1. Data acquisition and loading using PySpark
2. Data preprocessing:
   - Data transformation 
   - Imputation of missing values
3. Feature engineering
4. Exploratory data analysis 
5. Model development and validation
6. Interpretation of results

## Key Findings

1. Churn rates highest among "High Spend, Short Tenure" customers
2. Churn rate increases with higher monthly charges
3. Churn rate varies by invitation source - highest for merchant collaborations
4. Family member referrals are the most common source of new customers

## Predictive Modeling

- Tested logistic regression, decision tree, and random forest models
- Logistic regression had highest accuracy of 95.55%

## Recommendations

1. Revise pricing strategy for high-spending customers
2. Evaluate and improve merchant collaboration programs  
3. Incentivize family member referrals
4. Use predictive model to identify and proactively retain at-risk customers

## Technologies Used

- PySpark for data processing and analysis
- Spark SQL for data aggregation 
- GraphFrames for relationship analysis

## How to Run

1. Ensure PySpark and required libraries are installed
2. Run the CustomerChurnAnalysis.ipynb Jupyter notebook:

## Conclusion

Based on the analysis of customer churn data for the telecommunications company, we can draw the following conclusions:

This project provides a comprehensive analysis of customer churn patterns and factors for the telecommunications company. By implementing the insights and recommendations from this study, the company can:

1. Develop targeted retention strategies for high-risk customer segments, particularly those with high monthly charges and short tenure.

2. Revise pricing strategies and service offerings to better align with customer expectations and reduce churn among price-sensitive customers.

3. Optimize customer acquisition channels by focusing on family member referrals and reevaluating merchant collaboration programs that show higher churn rates.

4. Implement a predictive model to proactively identify customers at risk of churning, allowing for timely intervention and personalized retention efforts.

5. Enhance the onboarding experience and early engagement for new customers to improve long-term retention.

By leveraging these data-driven insights, the telecommunications company can make informed decisions to reduce churn rates, improve customer satisfaction, and ultimately enhance their customer retention efforts. This approach will enable the company to build stronger, more enduring relationships with their customers and improve overall business performance.
