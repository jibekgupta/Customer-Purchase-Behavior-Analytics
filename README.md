# Customer Purchase Behavior Analysis

## Executive Summary
This project analyzes 3.9K retail transactions to identify revenue drivers, discount impact, and subscription opportunities. Using Python for data preparation, SQL for business queries, and Power BI for visualization, the analysis surfaces actionable customer insights for marketing and growth teams.

## Business Question
How can customer shopping data be analyzed to uncover behavioral trends, strengthen customer engagement, and optimize marketing and product strategies?

## Dataset Overview
- 3,900 transactions across 18 attributes (demographics, product, discounts, shipping, reviews).
- Missing values in review ratings were imputed using category-level medians.
- Average purchase amount: $59.76; average review rating: 3.75.

## Approach
- **Python:** cleaned data, standardized columns, engineered `age_group` and `purchase_frequency_days`.
- **SQL:** answered stakeholder questions on revenue, discount impact, shipping, and loyalty.
- **Power BI:** built a dashboard with category performance, subscription adoption, and seasonality.

## Key Findings
- Clothing and Accessories are the top revenue-driving categories.
- Subscription adoption is low, indicating room for retention growth.
- Faster shipping options correlate with higher average spend.
- Seasonal purchasing trends are stable with modest spikes in Spring and Fall.
- Repeat purchase behavior suggests a strong loyal segment.

## Business Recommendations
- Strengthen subscription incentives to convert repeat customers.
- Implement loyalty programs targeted at high-frequency buyers.
- Optimize discounting for margin protection on discount-dependent items.
- Prioritize marketing spend toward top-performing categories.

## Skills Demonstrated
Data cleaning, feature engineering, SQL analytics, dashboarding, business storytelling.

## Repository Contents
- **Notebook:** `Customer_Shopping_Behavior_Analysis.ipynb`
- **SQL queries:** `Customer Purchase Behavior.sql`
- **Dashboard:** `customer_behavior_dashboard.pbix`
- **Dataset:** `customer_shopping_behavior.csv`
- **Reports:** `Business Problem Overview.pdf`, `Customer Purchase Behavior Analytics.pdf`

## Reproducibility
1. Install dependencies: `pip install -r requirements.txt`.
2. Open `Customer_Shopping_Behavior_Analysis.ipynb` and run top-to-bottom.
3. Optional: load the cleaned dataset into PostgreSQL and run `Customer Purchase Behavior.sql`.

## Dashboard Preview
Add a screenshot at `images/dashboard.png` and link it here:
`![Power BI Dashboard](images/dashboard.png)`

## SQL Highlights
The SQL file includes:
- Revenue by gender
- Discount sensitivity among high-value customers
- Subscription impact on revenue
- Top products by rating and discount dependency
