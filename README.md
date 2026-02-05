# Customer-Churn-Retention-Analysis
📌 Project Overview

Customer churn is a major challenge for subscription-based businesses. This project analyzes customer behavior to identify why customers leave, who is most at risk, and what factors drive retention, using SQL for data preparation and Power BI for visualization.

The goal is to provide actionable business insights that can help stakeholders reduce churn and improve customer lifetime value.

🎯 Business Objectives

Measure overall customer churn rate

Identify high-risk customer segments

Understand the impact of contract type, payment method, and services on churn

Provide visual insights to support retention strategies

🗂 Dataset Description

The dataset contains 800+ customer records with features covering:

Customer demographics (gender, senior citizen, region)

Subscription details (contract type, tenure, services)

Billing & payment information

Customer behavior (support tickets, call duration)

Churn status (Yes / No)

Target variable: Churn
https://drive.google.com/file/d/1z3L1jdphvK7VHp8fiQ6h40NOGro9_M27/view?usp=drive_link

🧹 Data Cleaning & Preparation (SQL)

Data preparation was performed using SQL, including:

Handling missing and inconsistent values

Standardizing categorical fields (Yes/No, contract types)

Calculating derived metrics such as:

Total Charges

Customer Lifetime Value (CLV)

Filtering invalid records (e.g., zero tenure)

SQL was used to generate clean, analysis-ready tables before visualization.
https://docs.google.com/document/d/1uuN1tjpL4_8R0wZn4gxsOSmZVk-R9h-F/edit?usp=drive_link&ouid=117508295274835040304&rtpof=true&sd=true

📐 Key KPIs

Total Customers

Churned Customers

Churn Rate (%)

Average Tenure

Average Monthly Charges

Customer Lifetime Value (CLV)

📊 Power BI Visualizations

The Power BI dashboard includes:

🔹 Executive KPIs

Total Customers

Churned Customers

Churn Rate (%)

🔹 Distribution Analysis

Donut Chart: Churn vs Retained Customers

Donut Chart: Churn by Contract Type

Donut Chart: Churn by Payment Method

Donut Chart: Churn by Internet Service

🔹 Driver Analysis

Decomposition Tree: Key drivers of churn

Treemap: Churn contribution by contract & service

🔹 Behavioral Analysis

Line Chart: Churn trend by tenure

Scatter Plot: High-risk customer segmentation

Bar Chart: Support tickets vs churn

🔹 Risk Analysis

Heatmap (Matrix): Churn rate by region and contract type

🔹 Lifecycle View

Funnel Chart: Customer retention funnel
<img width="1221" height="680" alt="Screenshot 2026-02-04 064709" src="https://github.com/user-attachments/assets/5358d6b1-4962-4398-b595-d4bd0e216b77" />
<img width="1212" height="677" alt="Screenshot 2026-02-04 064920" src="https://github.com/user-attachments/assets/2d29ea76-74a3-4200-b0ce-20b1dd0f3e93" />
<img width="1203" height="672" alt="Screenshot 2026-02-04 064941" src="https://github.com/user-attachments/assets/06527b07-8190-453a-82c3-98189e398ac3" />

💡 Key Insights

Month-to-month contracts show the highest churn rates

Customers with shorter tenure are more likely to churn

Higher monthly charges correlate with increased churn

Customers with frequent support issues are at higher risk

Certain payment methods are associated with higher churn


✅ Recommendations

Encourage long-term contracts through incentives

Introduce proactive engagement for early-tenure customers

Improve customer support responsiveness

Review pricing strategies for high-risk segments

🛠 Tools & Technologies

SQL: Data cleaning, transformation, KPI calculation

Power BI: Data modeling, DAX measures, interactive dashboards

Excel / CSV: Raw data storage
