📊 Customer Churn Analysis & Prediction
Overview

This project analyzes historical customer behavior to identify churn drivers and predict customers at risk of churning.
It combines machine learning (Python) with interactive Power BI dashboards to support data-driven retention decisions.

Business Objective

Understand why customers churn

Identify high-risk customer segments

Predict future churners

Enable proactive retention strategies

Tools & Tech Stack

Python: Pandas, NumPy, Scikit-Learn

ML Model: Random Forest Classifier

Visualization: Power BI

Data Source: Excel

Model Persistence: Joblib

Dashboards
1️⃣ Churn Analysis (Descriptive)

Provides a summary view of churn behavior:

KPIs: Total Customers, New Joiners, Total Churn, Churn Rate

Churn by:

Gender

Age Group

Tenure

Contract Type

Payment Method

Internet Type

Geography (Top States)

Churn Category & Reason

Purpose: Identify key churn drivers.
<img width="1156" height="652" alt="Screenshot 2026-02-08 092337" src="https://github.com/user-attachments/assets/3d4947d6-fc82-459a-b1fd-0e3db74091e8" />

2️⃣ Churn Prediction (Predictive)

Focuses on identifying customers likely to churn.

Model: Random Forest

Output: Binary churn prediction (0 = Stay, 1 = Churn)

Insights by:

Demographics

Tenure & contract

Payment behavior

Geography

Includes a Customers at Risk table with revenue and refund metrics.

Purpose: Enable targeted retention actions.

Workflow

Data ingestion & preprocessing

Categorical encoding

Model training & evaluation

Prediction on new customers

Export results

Visualization in Power BI
<img width="1160" height="659" alt="Screenshot 2026-02-08 092351" src="https://github.com/user-attachments/assets/a8c4381d-17b5-4696-ac7d-b292302454c2" />


Key Insights

Month-to-month contracts show the highest churn

Short tenure customers are more likely to churn

Payment method and internet type strongly influence churn

Geographic churn concentration varies significantly by state

Impact

Created a scalable churn prediction pipeline

Translated ML outputs into business-ready dashboards

Enabled identification of high-value customers at risk

Future Enhancements

Churn probability scoring

Feature importance analysis

Automated refresh using SQL

Model tuning & validation

Use Case

Applicable to:

Telecom

Subscription services



SaaS

Consulting & analytics roles
