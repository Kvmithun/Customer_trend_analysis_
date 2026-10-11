# Customer Shopping Behavior Analysis

An end-to-end data analytics project exploring customer shopping behavior using Python, SQL, PostgreSQL, Neon, and Power BI.

## Project Objective

Analyze customer purchase patterns to identify insights about spending, discounts, product reviews, shipping preferences, subscriptions, repeat purchases, and customer segments to support better marketing and customer-retention decisions.

## Tools & Technologies

- Python
- Pandas and NumPy
- Jupyter Notebook
- SQL
- PostgreSQL
- Neon (Cloud-Hosted PostgreSQL)
- Power BI

## Project Workflow

1. **Data Preparation:** Cleaned and explored the customer shopping dataset using Python.
2. **Database Integration:** Loaded the cleaned data into PostgreSQL.
3. **Cloud Migration:** Migrated the local `customer_behavior` database to Neon PostgreSQL using `pg_dump` and `pg_restore`.
4. **SQL Analysis:** Analyzed customer spending, revenue, discounts, product ratings, shipping, subscriptions, repeat purchases, and age-group revenue.
5. **Visualization:** Developed an interactive Power BI dashboard to present customer behavior and business metrics.
6. **Business Insights:** Identified patterns and recommendations to support data-driven decisions.

## Database Setup

- **Local Database:** `customer_behavior`
- **Cloud Provider:** Neon
- **Neon Database:** `neondb`
- **Table:** `public.customer`
- **Migration Tools:** `pg_dump` and `pg_restore`

The database was migrated to Neon, and the `public.customer` table was successfully queried in the Neon SQL Editor.

## SQL Analysis

The SQL queries cover:

- Sample customer records
- Revenue by gender
- High-spending customers using discounts
- Highest-rated products
- Average purchase amount by shipping type
- Subscriber vs. non-subscriber spending and revenue
- Products with the highest discount-use rates
- New, Returning, and Loyal customer segmentation
- Top-selling products by category
- Repeat buyers by subscription status
- Revenue contribution by age group

## Power BI Dashboard

The interactive dashboard presents customer metrics, subscription distribution, revenue by category, sales by category, and revenue and sales by age group. Slicers allow filtering by subscription status, gender, category, and shipping type.

## Project Files

- **Python Notebook:** `Customer_shopping_behavior_analysis.ipynb`
- **SQL Queries:** `customer_trend_analysis.sql`
- **Dataset:** Available in the `dataset/` folder
- **Project Report:** Available in the `Project_report/` folder
- **Project Presentation:** Available in the `Project_presentation/` folder
- **Power BI Dashboard:** Available in the `dashboard/` folder
- **Business Problem Statement:** Available in the `probelm-statement/` folder
- **License:** `LICENSE`

Refer to the project report for detailed methodology and analysis, and the presentation for summarized findings and business recommendations.

## Author

**Mithun KV**

GitHub: [@Kvmithun](https://github.com/Kvmithun)