# Telco-Customer-Churn-Analysis
Telecom Customer Churn Analysis involved exploring telecom customer data to identify key factors influencing churn such as contract type, tenure, and monthly charges. Insights from EDA and visualizations were used to recommend strategies for improving customer retention.

📌 Project Title:

Customer Churn Analysis for a Telecom Company

🧾 Brief One-Line Summary:

Analyzed customer behavior to identify key churn drivers and recommend retention strategies using data visualization and statistical analysis.

🔍 Overview:

Customer churn is a major challenge for telecom companies as acquiring new customers is more expensive than retaining existing ones. This project aims to identify the primary reasons behind customer churn using exploratory data analysis (EDA) and data visualization techniques. The objective is to help the business take proactive steps to reduce churn and increase customer lifetime value.

❗ Problem Statement:

The telecom company is facing a high churn rate, especially among new customers with short tenure and specific contract types. The goal is to analyze customer data to uncover churn patterns and deliver actionable insights for customer retention.

📂 Dataset:

Name: Telco Customer Churn Dataset
Records: 7,043 customers
Features: Customer demographics, account info, services subscribed (internet, phone), tenure, charges, contract type, and churn status
Source: Public dataset (Kaggle or similar platforms)

🧰 Tools and Technologies Used:

Languages: Python
Libraries: Pandas, NumPy, Seaborn, Matplotlib
Visualization Tools: Seaborn & Matplotlib
Notebook: Jupyter Notebook / Google Colab

🧪 Methods:

Data Cleaning & Preparation:

Replaced blank values with 0 in TotalCharges
Converted data types (e.g., TotalCharges to float)
Transformed SeniorCitizen from numeric to categorical (yes/no)
Removed extra white spaces and standardized binary variables

Exploratory Data Analysis (EDA):

Created 15+ visualizations (count plots, box plots, KDE plots, pair plots, and correlation heatmap)
Compared churn with features like Contract, MonthlyCharges, Tenure, Dependents, SeniorCitizen, etc.
Hypothesis Testing:

Performed statistical tests to verify assumptions such as “Short-tenure customers churn more frequently”

📈 Key Insights from Analysis:

Customers with monthly contracts and tenure less than 3 months are highly likely to churn.
Customers without dependents or partners showed higher churn rates.
Senior citizens and high monthly charges correlate with higher churn.
Electronic check as a payment method is associated with more churn than other methods.
Churn is less in long-term contracts (1-year or 2-year plans).

📊 Dashboard/Model/Output:

Created 15+ analytical charts including:

Churn distribution
Monthly Charges vs. Churn (KDE plot)
Contract Type vs. Churn (Count plot)
Correlation heatmap of numeric features
Pair plot of tenure, monthly charges, total charges vs. churn
Each chart includes business interpretation and actionable insights.

🛠️ How to Run This Project?

Open the Jupyter Notebook or Google Colab
Upload the dataset (Customer Churn.csv)
Run the script to perform cleaning, transformation, and visualizations
Interpret insights from charts and plots generated at each step

✅ Results & Conclusion:

The project successfully identified tenure, contract type, monthly charges, and payment method as the most significant factors influencing churn. These insights can guide the telecom company to introduce:

Loyalty programs for new customers
Discounts for high-risk customer segments
Incentives for switching to long-term contracts
This analysis enables data-driven decisions for reducing churn and improving customer retention.
