#  Retail Consumer Behavior Analytics Dashboard

#  Project Overview

This project focuses on analysing consumer shopping behavior to uncover patterns that influence purchasing decisions, customer loyalty, and sales performance. The analysis transforms raw transactional data into actionable insights that support better marketing, product, and customer engagement strategies.

#  Business Problem

A retail company aims to better understand customer shopping behavior in order to improve sales performance, increase customer satisfaction, and strengthen long term loyalty. Management observed shifts in purchasing patterns across demographics, product categories, and sales channels including both online and in store transactions. There is a need to identify which factors such as discounts, product reviews, seasonal trends, and payment preferences influence purchasing decisions and repeat purchases.

#  Objective

Provide business stakeholders with actionable insights into consumer behavior and purchasing trends to support improved customer engagement, optimized marketing strategies, and better product positioning.

#  Scope

Focus Area: Consumer Behavior and Retail Analytics

#  Dashboard Preview

Dashboard file available in the powerbi folder.
#  Key Metrics (KPIs)

Total Revenue by Gender

Average Purchase Amount by Shipping Type

Average Spend & Total Revenue for Subscribers vs Non-Subscribers

Number of Customers by Segment (New, Returning, Loyal)

Revenue Contribution by Age Group

Top Products by Average Review Rating

Top Products by Category

Discount Rate by Product

High-Value Discount Purchases (customers spending above average with discounts)

Subscription Rate among Repeat Buyers


#  Data Preparation & Modeling

Data preparation and exploratory analysis were performed using Python. The analysis notebook is located in the python folder.

Cleaned and transformed raw consumer data to ensure accuracy and consistency

Handled missing values and corrected inconsistent entries

Structured data to support efficient querying and reporting

Performed exploratory analysis to identify trends and relationships across customer segments and purchasing behavior

The original dataset used for analysis is stored in the data folder.


#  Data Analysis

SQL was used to organize and analyse transactional data. All analytical queries are available in the sql folder.

Structured datasets to reflect business transactions and customer activity

Developed queries to analyse customer segments, loyalty patterns, and purchase drivers

Extracted insights to answer key business questions related to sales performance and consumer engagement


#  Visualization & Insights

An interactive Power BI dashboard was developed to present key trends and performance indicators. The dashboard file is located in the powerbi folder.

Visualised sales trends across demographics, product categories, and sales channels

Enabled stakeholders to explore consumer behavior through interactive filtering

Supported data driven decision making through clear visual storytelling


#  Tools & Technology

Python (Data Cleaning, Exploratory Data Analysis)

SQL (Data Analysis and Querying)

Power BI (Data Modeling, DAX Calculations, Interactive Reporting)

Data Model Type: Star Schema


#  Project Structure

```
retail-consumer-behavior-analytics/
 ├── README.md
 ├── data/
 │   └── customer_shopping_behavior.csv
 ├── python/
 │   └── Customer_Shopping_Behavior_Analysis.ipynb
 ├── sql/
 │   └── customer_behavior_sql_queries.sql
 ├── powerbi/
 │   └── customer_behavior_dashboard.pbix
 └── documentation/
     ├── Business Problem Document.pdf
     ├── Customer Shopping Behavior Analysis.pdf
     └── Customer_Shopping_Behavior_Analysis.pptx
 ```    

#  Insights & Narrative

The analysis revealed several actionable patterns in customer behavior. 
Subscribers generate higher revenue and demonstrate stronger loyalty compared to non-subscribers, suggesting that promoting exclusive benefits for subscribers could increase engagement and lifetime value. 

Repeat customers, especially those with more than five previous purchases, are a high-value segment, and rewarding them through loyalty programs or targeted incentives can improve retention. 

Certain customer segments, including express shipping users, consistently contribute more to total revenue, indicating that focusing marketing and promotions on these segments can maximize returns. 

Products with the highest review ratings perform well in purchases, so featuring these products in campaigns can drive additional sales and improve customer satisfaction. Overall, these insights support strategies to increase sales, retain customers, and improve engagement.


#  Recommendations

Promote exclusive benefits for subscribers.

Reward repeat buyers to icrease retention.

Focus on high-revenue segments abd express users.

Highlight top-rated products in campaigns.
