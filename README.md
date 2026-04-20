# Customer-Churn-Analysis

Customer Churn Analysis & Retention Strategy 📉

Tech Stack: SQL Server | Power BI 

📋 Project Overview

This project focuses on identifying and mitigating customer attrition for a telecommunications provider. By analyzing a dataset of 6,418 customers, I developed an end-to-end business intelligence solution that identifies why customers are leaving and quantifies the financial impact of churn. The project resulted in a data-driven retention strategy aimed at saving $3.41M in at-risk revenue.

🚀 Key Insights & Business Impact

Churn Overview: Identified a 26.99% overall churn rate, with a total revenue loss of $3.41 Million attributed to churned customers.

Contract Risk: Discovered that Month-to-Month contracts carry the highest risk (46.5% churn rate), while Two-Year contracts offer near-perfect retention (97%+).

Competitive Pressure: Pinpointed that Competitor offers and better devices account for nearly 45% of all churn, indicating a need for more competitive hardware bundles.

Customer Service Impact: Uncovered that 12% of churn is driven by "Support Attitude," providing a clear mandate for improved staff training and customer service protocols.

High-Value Markets: Identified Uttar Pradesh and Tamil Nadu as the largest revenue contributors ($1.9M+ each), necessitating focused infrastructure investment in these regions.

🛠️ Data Pipeline & Workflow

1. Data Cleaning & ETL (SQL Server)
Developed a structured ETL pipeline to transform raw data into production-ready tables:

Staging to Production: Migrated data from stg_Churn to prod_Churn using ISNULL functions to standardize categorical values (e.g., handling missing values for "Online Security" or "Value Deals").

Data Quality: Performed null-value audits across 30+ columns to ensure data integrity before visualization.

Reporting Views: Created optimized SQL Views (vw_ChurnData, vw_JoinData) to separate historical churn analysis from new customer acquisition trends.


2. Business Intelligence Dashboard (Power BI)

Built a dynamic dashboard (analyzing $19.47M in revenue) featuring:

KPI Summary Cards: Instant visibility into Total Customers, New Joinees, and Churn Rate.

Churn Analysis: Breakdown of churn by category (Competitor, Dissatisfaction, Price, etc.).

Geographic Mapping: Interactive state-wise distribution of the customer base.

Service Usage Trends: Analysis of which services (Internet, Phone, Streaming) correlate most with customer loyalty.

💡 Recommendations

Incentivize Long-term Contracts: Offer discounts or "Value Deals" to migrate Month-to-Month customers to One or Two-Year plans.

Hardware Upgrades: Address the "Competitor had better devices" churn driver by offering loyalty-based device upgrades for customers with high tenure.

Targeted Retention for Seniors: Develop simplified service bundles or dedicated support lines for the 60+ demographic to reduce their higher-than-average churn.
