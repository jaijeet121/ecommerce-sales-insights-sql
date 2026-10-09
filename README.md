# Target Brazil E-commerce Data Analysis using SQL

## 📌 Project Overview

This project analyzes Target's e-commerce operations in Brazil using SQL to uncover business insights related to sales performance, customer distribution, order trends, shipping costs, delivery efficiency, and payment behavior.

The analysis covers approximately 100,000 orders placed between 2016 and 2018. The objective is to understand customer purchasing patterns, evaluate logistics performance, and identify opportunities to improve business operations.

## 🎯 Business Objectives

- Analyze order trends and monthly seasonality.
- Understand customer distribution across Brazilian states.
- Identify customer purchasing patterns by time of day.
- Evaluate order value and freight costs across states.
- Measure delivery time and compare actual delivery dates with estimated dates.
- Analyze payment methods and installment preferences.
- Develop actionable recommendations based on SQL analysis.

## 🛠️ Tools & Technologies

- **SQL** – Data querying, transformation, aggregation, and analysis.
- **Google BigQuery** – SQL execution and data exploration.
- **GitHub** – Project documentation and version control.

## 📂 Dataset Overview

The dataset contains information about Target's Brazilian e-commerce operations, including the following tables:

| Table | Description |
|---|---|
| `customers` | Customer location and identification details |
| `orders` | Order status, purchase timestamps, and delivery dates |
| `order_items` | Product prices and freight values |
| `payments` | Payment types, values, and installment details |
| Product and review-related data | Product attributes and customer feedback |

The analysis focuses primarily on customers, orders, order items, and payments.


## 💡 Key Insights

- Order activity showed growth over the analyzed period, with strong growth reported between 2017 and 2018.
- Shopping activity increased from January through August before declining.
- Afternoon and evening shopping patterns provide useful opportunities for targeted promotions.
- Customer activity varied across Brazilian states.
- Shipping costs and delivery times highlighted potential logistics challenges in some regions.
- Credit cards were identified as the most popular payment method.
- Installment payments represented an important aspect of customer payment behavior.
- Some orders arrived before their estimated delivery dates, while others experienced longer delivery times.

## 📈 Business Recommendations

1. **Time-Based Promotions:** Schedule targeted offers during high-activity shopping hours.
2. **Logistics Optimization:** Investigate high-freight-cost regions and evaluate opportunities for better warehouse placement.
3. **Delivery Improvement:** Use historical delivery data to improve estimated delivery dates and reduce delays.
4. **Flexible Payments:** Make installment options more visible to customers.
5. **Regional Expansion:** Investigate states with lower order volumes to identify opportunities for customer acquisition.
6. **Customer Trust:** Highlight reliable, on-time deliveries in marketing campaigns when supported by performance data.

## 🧠 Skills Demonstrated

- SQL querying and data exploration
- Filtering, grouping, and aggregation
- Date and time functions
- Joins across relational tables
- Common Table Expressions (CTEs)
- Window functions such as `LEAD()`
- Business KPI analysis
- E-commerce and logistics analytics
- Translating data insights into business recommendations

## 📁 Repository Structure

```text
target-brazil-ecommerce-sql-analysis/
│
├── README.md
├── sql/
│   └── analysis_queries.sql
├── images/
│   └── visualizations/
└── dataset/
    └── README.md
    
