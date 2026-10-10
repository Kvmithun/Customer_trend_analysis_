# Customer Shopping Behavior Analysis

An end-to-end data analytics project exploring customer shopping
behavior using Python, SQL, PostgreSQL, Neon, and Power BI.

## Project Objective

Analyze customer purchase patterns to identify useful insights about
spending, discounts, product reviews, shipping preferences,
subscriptions, repeat purchases, and customer segments. The goal is to
support better marketing, product, and customer-retention decisions.

## Tools & Technologies

-   Python
-   Pandas and NumPy
-   Jupyter Notebook
-   SQL
-   PostgreSQL
-   Neon (cloud-hosted PostgreSQL)
-   Power BI

## Project Workflow

1.  **Data preparation:** Clean and explore the raw customer shopping
    dataset in Python.
2.  **Database:** Store the customer data in PostgreSQL.
3.  **Cloud migration:** Export the local `customer_behavior` database
    and restore it to Neon PostgreSQL.
4.  **SQL analysis:** Use SQL queries to analyze customer spending,
    discounts, product ratings, shipping, subscriptions, repeat
    purchases, and age-group revenue.
5.  **Visualization:** Connect the database to Power BI and build an
    interactive dashboard.
6.  **Insights:** Translate the analysis into business findings and
    recommendations.

## Current Database Setup

-   **Local database:** `customer_behavior`
-   **Cloud database provider:** Neon
-   **Neon database:** `neondb`
-   **Migrated table:** `public.customer`
-   **Migration method:** PostgreSQL `pg_dump` custom-format backup and
    `pg_restore`

The local database backup was restored to Neon, and the
`public.customer` table was queried successfully in the Neon SQL Editor.

**Power BI connection and scheduled refresh:** These are still to be
configured and verified. A successful Neon migration does not by itself
confirm that Power BI Service refresh is working.

## SQL Analysis

The SQL queries cover topics including:

-   Sample customer records
-   Revenue by gender
-   Customers using discounts who spend above the average
-   Highest-rated purchased products
-   Average purchase amount by shipping type
-   Subscriber versus non-subscriber spending and revenue
-   Products with the highest discount-use rates
-   New, returning, and loyal customer segmentation
-   Top purchased products within each category
-   Subscription status among repeat buyers
-   Revenue contribution by age group

The SQL source file is `customer_trend_analysis(1).sql`.

## Project Files

-   `Customer_shopping_behavior_analysis(1).ipynb` --- Python analysis
    notebook
-   `customer_trend_analysis(1).sql` --- SQL business analysis queries
-   `customer_shopping_behavior.csv` --- Source dataset
-   `Business Problem  Document.pdf` --- Business problem statement
-   `LICENSE` --- Project license

Update these names if you rename the files in your repository. Add your
Power BI report file (`.pbix`) and dashboard screenshots after the
dashboard has been created.

## Business Questions

This project explores how customer data can help a retail business:

-   Understand spending patterns across customer groups
-   Evaluate discount usage and purchase behavior
-   Compare subscriber and non-subscriber spending
-   Explore product ratings and purchasing patterns
-   Identify repeat customers and customer segments
-   Compare revenue across age groups

## Next Steps

-   Verify row counts and sample records in Neon against the local
    database.
-   Connect Power BI to the Neon PostgreSQL database.
-   Configure and test scheduled refresh in Power BI Service.
-   Build the dashboard and document the key insights and
    recommendations.

## Author

Mithun KV
