```markdown
# Brazilian E-Commerce Analysis: Olist Dataset

## Introduction
This project delves into the Olist E-Commerce dataset, comprising 100,000 orders placed across multiple marketplaces in Brazil between 2016 and 2018. The primary objective is to conduct a comprehensive analysis of customer behavior, delivery performance, and revenue trends. This analysis, utilizing a combination of SQL (SQLite) and Python (Pandas/Seaborn), aims to identify key areas for growth, pinpoint logistics bottlenecks, and understand customer retention patterns.

## Dataset
The dataset includes several tables related to Olist's E-Commerce activities:
- `customers`: Customer unique IDs and their locations.
- `orders`: Order details, including status and timestamps.
- `items`: Information about items within each order, including price and freight value.

## Analysis Phases

The analysis was structured into several key phases:
1.  **Data Cleaning & Schema Verification**: Ensuring data quality, verifying primary key uniqueness, and converting date strings to datetime objects.
2.  **Exploratory Data Analysis (EDA)**: Understanding customer distribution by state and summarizing pricing metrics.
3.  **Order Status Analysis**: Examining order fulfillment rates and the distribution of various order statuses.
4.  **Advanced Insights**: Utilizing SQL subqueries and Pandas merges to analyze churn rates and delivery performance (e.g., delivery delays by state).
5.  **Data Visualization**: Creating visual representations of key findings, such as monthly revenue trends, product revenue contribution (Pareto analysis), and peak shopping hours.

## Key Findings

*   **Revenue Dynamics**: The project identified strong monthly revenue growth trends. A significant Pareto effect was observed, where approximately 20% of products contribute to 80% of the total revenue.
*   **Logistics Performance**: The majority of orders (97.02%) are delivered successfully. While the average delivery is generally ahead of schedule, specific northern regions (e.g., Acre, Rondônia) exhibit significantly higher lead times compared to others.
*   **Customer Retention**: Analysis revealed a notable churn rate, with over 43,000 unique customers from 2017 not placing orders in 2018. This represents a significant opportunity for re-engagement strategies.
*   **Shopping Patterns**: Peak order volumes are concentrated during weekday afternoons (Monday-Friday, 10 AM - 4 PM), suggesting optimal windows for targeted marketing campaigns and flash sales.
*   **Order Size**: The average number of items per order is low, at approximately 1.14 items.

## Business Recommendations

Based on the analysis, the following actionable recommendations are proposed:

1.  **Implement a Customer Win-Back Program**: Launch targeted email marketing or discount campaigns for the 43,000+ customers who churned between 2017 and 2018 to revitalize their lifetime value.
2.  **Optimize Logistics for Northern Regions**: Investigate and potentially partner with local distribution centers in states like Acre (AC) and Rondônia (RO) to reduce delivery lead times and improve customer satisfaction in these areas.
3.  **Bundle High-Volume Products**: Develop 'frequently bought together' product bundles, leveraging the insight that 20% of products drive 80% of revenue and the average order contains few items, to increase the Average Order Value (AOV).

```
