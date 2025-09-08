# SpicyFood🍜: Exploring Customer Segmentation with a Tableau Dashboard

## Table of Contents 
- [Background](#background)
- [Project Objectives](#project-objectives)
- [Data Collection and Understanding](#data-collection-and-understanding)
- [Dashboard Preview](#dashboard-preview)
- [Key Metrics Overview](#key-metrics-overview)
- [Summary of Insights](#summary-of-insights)
- [Recommended Retention Strategies](#recommended-retention-strategies)
- [Conclusion](#conclusion)

## Background
SpicyFood is a fictional FoodTech Company. 

The company’s management wanted to gain deeper insights into customer behavior, purchasing patterns, and overall value contribution. Specifically, they were interested in:

- Identifying their most valuable customers.
- Understanding customer demographics such as age and gender.
- Segmenting customers based on recency, frequency, and monetary value.
- Finding opportunities to retain at-risk customers and convert occasional buyers into loyal ones.

To address this, SpicyFood engaged in a Customer Segmentation project using the RFM Analysis model. By leveraging Tableau, the project translates raw transactional data into an interactive dashboard that provides actionable insights for decision-making.

Let’s first take a look at what **Recency, Frequency, and Monetary** are:
- **(Recency) R —** How recent was the last purchase of a customer?
- **(Frequency) F —** How often does a customer make a transaction?
- **(Monetary) M —** How much money does a customer spend on a purchase?

**RFM Analysis is often used by companies when they have to -**
- Develop retention campaigns aimed at at-risk customers to reduce churn.
- Personalize marketing strategies to enhance engagement with top customers.
- Optimize marketing budgets by prioritizing high-value users for better ROI.
- Identify customer segments to tailor promotions and offers effectively.
- Improve customer lifetime value (CLV) by targeting the right audience with data-driven insights.

## Project Objectives
- Perform RFM segmentation to categorize customers into tiers such as **Champions, Loyal Customers, Potential Loyalists, Promising, and At Risk**.
- Visualize customer segmentation using an interactive Tableau dashboard.
- Provide insights to help businesses understand customer behavior and improve decision-making.

## Data Collection and Understanding
The dataset includes essential details like Customer ID, Purchase Frequency, Bill Amount, Recency, and other relevant attributes.

The dataset used for this analysis includes the following fields:

1. **Customer ID:** Unique identifier for each customer.

2. **Purchase Frequency:** The number of purchases a customer makes.

3. **Bill Amount:** Total monetary value spent by the customer.

4. **Recent Purchase Date:** The customer’s latest purchase date.

5. **Rank_Recency:** Ranking based on the recency of purchases.

6. **Rank_Frequency:** Ranking based on purchase frequency.

7. **Rank_Spending:** Ranking based on the total spending amount.

8. **Average of Rank:** Average rank across recency, frequency, and spending.

9. **Overall Rank:** Combined rank for RFM segmentation.

10. **Customer Tiers:** Segmented customer groups based on RFM scores.

11. **Gender:** Gender of the customer.

12. **Age:** Age of the customer.

## Dashboard Preview

<img width="1850" height="768" alt="Dashboard" src="https://github.com/user-attachments/assets/ea3a22ac-5d83-4b54-bc82-28bcf122e550" />

### View Live Tableau Dashboard [Here](https://public.tableau.com/views/Kshitija_SpicyFood_Dashboard1_6/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Key Metrics Overview

<img width="1626" height="163" alt="image" src="https://github.com/user-attachments/assets/7f1e7b14-2de6-4884-9363-5010a8a54853" />

- **Total Revenue:** Customers have made purchases totaling Rs. 179,500.
- **Total Orders:** The total number of orders placed is 107.
- **Unique Customer Base:** SpicyFood serves 35 unique customers, highlighting its niche market.
- **Average Purchase Value:** On average, each customer spends Rs. 5,129 per transaction.

## Summary of Insights

### Customer Segmentation Breakdown
<img width="1172" height="301" alt="unnamed" src="https://github.com/user-attachments/assets/adddc3f0-0c3d-4bcd-8b68-69f6412012eb" />

As we already know, customers are segmented into 5 different categories, such as **Champions, Loyal Customers, Potential Loyalists, Promising, and At Risk**.

#### 1. Champions 

<img width="427" height="227" alt="unnamed (1)" src="https://github.com/user-attachments/assets/ff45bf21-af17-4749-932b-088815f012a7" />

- These customers make up 22% of the customer base and contribute to the majority of revenue.

- They are frequent buyers with high spending and recent purchases, making them ideal for loyalty programs or exclusive offers.

#### 2. Loyal Customers
<img width="587" height="249" alt="unnamed (2)" src="https://github.com/user-attachments/assets/bfcc27d1-5f1f-4911-be1b-459beb681f44" />

- This group consistently makes repeat purchases and represents a significant portion of long-term revenue.

- Retaining them through rewards or early access to products can strengthen their loyalty even further.

#### 3. Potential Loyalist
<img width="557" height="278" alt="unnamed (3)" src="https://github.com/user-attachments/assets/ca8a8957-9b01-45ca-b5f9-6361610e68f4" />

- Customers in this group show high potential to become Champions.

- Strategies such as personalized marketing or small incentives (e.g., free shipping or discounts) could encourage them to purchase more frequently.

#### 4. Promising
<img width="528" height="261" alt="unnamed (4)" src="https://github.com/user-attachments/assets/243594ad-8604-4ba9-a680-056e29a632cd" />

- These are new or occasional buyers with medium spending levels.

- Engaging them through follow-ups, product recommendations, or introductory offers can drive higher retention.

#### 5. At Risk
<img width="459" height="210" alt="unnamed (5)" src="https://github.com/user-attachments/assets/27d3ad5d-cbad-4140-943c-c91d4d621402" />

- This segment includes customers with low recent activity but medium or high spending in the past.

- Re-engagement campaigns, such as email reminders, exclusive discounts, or personalized offers, could win them back.

### Spending Patterns

<img width="668" height="290" alt="unnamed (6)" src="https://github.com/user-attachments/assets/a49bfbb8-4a5e-45c3-a7d9-f2e38bf8ea83" />

- Loyal Customers and Champions have the highest spending levels, and their purchase frequency shows consistent growth.

### Demographics patterns

<img width="787" height="347" alt="unnamed (7)" src="https://github.com/user-attachments/assets/3c0fcfab-6393-4ded-ae6e-ba16b3d13502" />

- Champions, Potential Loyal Customers, and Promising are predominantly Teenagers, indicating a strong purchasing power in this demographic.

- Male customers slightly dominate the Champion segment, while females are more prevalent in the Potential Loyalist and Promising groups.

## Recommended Retention Strategies
- **Champions:** SpicyFood should enhance its loyalty by offering VIP programs, exclusive deals, and early access to new products.

- **At-Risk Customers:** Implement reactivation campaigns with targeted discounts and reminders of past positive experiences to encourage repeat purchases.

- **Promising Customers:** Build trust and engagement through personalized recommendations and welcome campaigns to nurture long-term relationships

## Conclusion
With this interactive Tableau dashboard, SpicyFood’s management can track customer trends, monitor spending behavior, and implement effective retention strategies. By continuously analyzing these insights, the company can foster long-term customer loyalty and maximize growth opportunities.

