# Customer Behaviour Analysis

Analyzed customer shopping patterns using Python and SQL, and built an interactive Power BI dashboard to support data-driven business decisions.


## Project Overview

This project analyzes the shopping behavior of 3,900 customers to uncover key insights related to revenue, purchasing patterns, discount impact, and customer segmentation. Using Python, SQL, and Power BI, the project walks through the full data analytics lifecycle — from data cleaning and feature engineering to dashboard creation and business recommendations.

## Key Objectives

- Understand customer purchasing patterns and revenue trends
- Identify discount effectiveness and its impact on profitability
- Compare subscriber vs. non-subscriber behavior
- Segment customers based on demographics, behavior, and purchase history
- Build a dashboard to help stakeholders make data-driven decisions

## Tech Stack

| Category | Tools |
|---|---|
| Programming | Python (Pandas, NumPy) |
| Database | PostgreSQL |
| Visualization | Power BI |

## Dataset Summary

| Detail | Value |
|---|---|
| Rows | 3,900 |
| Columns | 18 |
| Missing values | 37 (in `Review Rating`) |

**Key features:**

- **Customer demographics:** Age, Gender, Location, Subscription Status
- **Purchase details:** Category, Purchase Amount, Season, Size, Color
- **Shopping behavior:** Discount Applied, Promo Code, Previous Purchases, Review Rating, Shipping Type

## Data Cleaning & Preparation (Python)

- Loaded and explored the dataset using `pandas`
- Imputed missing values in `Review Rating` using category-wise medians
- Standardized column names to `snake_case`
- Engineered new features:
  - `age_group` (binned age categories)
  - `purchase_frequency_days` (derived from purchase dates)
- Removed redundant columns (e.g., `promo_code_used`)
- Exported the cleaned dataset to PostgreSQL for further analysis

## SQL Analysis

Conducted 10+ business-focused SQL queries, including:

1. Revenue comparison by gender
2. High-spending discount users
3. Top 5 highest-rated products
4. Standard vs. Express shipping purchase behavior
5. Subscriber vs. non-subscriber average spend
6. Top products within each category
7. Revenue contribution by age group
8. Customer segmentation (New, Returning, Loyal)
9. Discount-dependent products
10. Repeat buyers and subscription likelihood

## Power BI Dashboard

Built an interactive Power BI dashboard featuring:

- Revenue by Age Group
- Revenue by Subscription Status
- Sales by Product Category
- Profit & Discount Impact
- Customer Segmentation
- Discount Utilization Analysis

## Key Insights

- High discounts caused losses in the Enterprise segment, indicating a need to balance discounts with profitability
- Subscribers consistently generated higher average revenue, suggesting strong potential for subscription marketing
- Express shipping customers had higher purchase amounts, making them a high-value segment
- Top-rated products tended to convert repeat buyers more effectively
- Young adult and adult age groups contributed the most revenue

## Business Recommendations

- Optimize discount strategies to avoid profit loss in certain customer segments
- Boost subscriptions through exclusive offers and targeted campaigns
- Implement a loyalty program to convert returning buyers into long-term customers
- Promote top-performing products to drive higher sales
- Use targeted marketing for high-value demographics and shipping preferences

## Author

**Sourav Singh**
Aspiring Data Analyst skilled in SQL, Python, Power BI, and Excel.
Interested in transforming raw data into actionable insights for business growth.
