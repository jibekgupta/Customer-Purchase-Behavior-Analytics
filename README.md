# Customer Purchase Behavior Analysis

## Project Overview
This project analyzes customer purchase behavior using transactional retail data to generate actionable insights that support customer targeting, pricing, and subscription strategy decisions. The analysis focuses on understanding revenue drivers, purchasing patterns, discount usage, and customer loyalty to help businesses optimize growth and retention efforts.

---

## Business Objective and Decision Question

**Primary Business Objective**
Identify high-value customer segments and purchasing drivers in order to inform targeted retention strategies, discount optimization, and subscription growth.

**Primary Stakeholder**
Marketing and Growth Analytics teams responsible for customer engagement and revenue optimization.

**Key Decision Questions**
1. Which customer segments contribute the most to overall revenue and average order value?
2. Do discounts meaningfully increase customer spend, or do they primarily reduce margins?
3. How does subscription status relate to purchasing frequency and customer value?

---

## Key Metrics Defined
The following metrics were used throughout the analysis to evaluate customer behavior and revenue performance:
- **Total Revenue:** Sum of purchase amounts across all completed transactions. Used to identify high-impact customer segments and product categories.

- **Average Order Value (AOV):** Total revenue divided by number of orders. Used to assess spending behavior across customer groups and purchasing channels.

- **Purchase Frequency:** Number of orders per customer over the observed period. Used to distinguish between new, returning, and loyal customers.

- **Discount Usage Rate:** Percentage of transactions that included a discount. Used to evaluate customer sensitivity to promotions and the effectiveness of discounting strategies.

- **Subscription Rate:** Proportion of customers enrolled in a subscription program. Used to analyze the relationship between subscriptions, purchase frequency, and customer value.

---

## Dataset Summary
- 3,900 customer transactions  
- 18 features including demographics, purchase details, discounts, reviews, shipping type, and subscription status  
- Minor missing values in review ratings, handled during preprocessing  

---

## Tools & Technologies
- **Python:** Pandas, NumPy  
- **SQL:** PostgreSQL  
- **Visualization:** Power BI  
- **Environment:** Jupyter Notebook  

---

## Project Workflow

### 1. Data Preparation (Python)
- Cleaned and standardized raw transactional data  
- Handled missing values and validated data consistency  
- Engineered features such as age groups and purchase frequency  
- Exported cleaned data to PostgreSQL for analysis  

### 2. Data Analysis (SQL)
- Analyzed revenue and average spend by customer demographics  
- Identified high-spending customers and discount-driven products  
- Segmented customers into New, Returning, and Loyal groups  
- Compared purchasing behavior across shipping types and seasons  

### 3. Visualization (Power BI)
- Built an interactive dashboard summarizing key business metrics  
- Visualized revenue and sales by category and season  
- Analyzed subscription distribution and customer behavior  
- Enabled dynamic filtering by demographics, category, and shipping type  

---

## Key Insights
- Clothing and Accessories generate the highest revenue  
- Subscription adoption remains low, indicating growth opportunity  
- Customers using faster shipping options tend to spend more  
- Seasonal purchasing patterns are relatively consistent  
- Strong repeat purchase behavior highlights customer loyalty  

---

## Business Recommendations
- Strengthen subscription incentives to improve retention  
- Introduce loyalty programs for repeat customers  
- Optimize discount strategies to protect profit margins  
- Focus marketing efforts on high-performing product categories  
- Leverage demographic insights for targeted campaigns  

---

