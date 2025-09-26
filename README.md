# Online-Retail-Orders-Analysis
SQL project analyzing an online retail store’s orders database to extract insights on sales, customers, and payments. Includes queries, ERD, Excel dashboards, and a case study report.
# 🛒 Online Retail Orders Analysis

## 📌 Project Overview
This project analyzes the **order management system** of an online retail store using **SQL, MySQL Workbench, and Excel**. The goal is to extract **business insights** from sales, customers, and payment data to support **data-driven decision making**.

- Investigated sales trends and top-performing products
- Segmented customers (new vs repeat)
- Analyzed payment method success and failure
- Presented insights in a professional Excel dashboard

## 🔧 Tech Stack & Skills
- **SQL:** Joins, Subqueries, Aggregations, Clauses (`WHERE`, `GROUP BY`, `HAVING`)
- **RDBMS:** MySQL Workbench
- **Excel:** Pivot Tables, Charts, Interactive Dashboard

## 📂 Dataset & Schema
The database includes the following tables:

| Table         | Key Columns                              |
|---------------|------------------------------------------|
| Orders        | order_id, customer_id, order_date, status|
| Order_Items   | order_id, product_id, quantity, price    |
| Customers     | customer_id, name, location, signup_date |
| Products      | product_id, category, brand, unit_price  |
| Payments      | order_id, payment_method, payment_status |

📊 *Entity Relationship Diagram (ERD)*  
*(Insert ERD image here)*

## 📊 Key Business Questions & SQL Solutions
1. **Monthly Revenue Trends**
   - Query: Total revenue per month using JOINs and SUM aggregation
   - Insight: Sales peak during Nov–Dec (holiday season)

2. **Top 10 Products by Revenue**
   - Query: Aggregated revenue per product
   - Insight: Electronics dominate sales; Smartphones lead

3. **Customer Segmentation (New vs Repeat)**
   - Query: COUNT of orders per customer
   - Insight: Repeat customers contribute **60%+ of revenue**

4. **Payment Method Analysis**
   - Query: Success vs failure count per payment method
   - Insight: Credit cards are most reliable; COD has higher failure rates

*(Full SQL scripts in `/SQL` folder)*

## 📈 Excel Dashboard
The dashboard includes:
- Monthly revenue trends 📈
- Top products bar chart 🛍️
- Customer type distribution 👥
- Payment method success/failure 💳
- Key metrics: Total Revenue, Avg Order Value, Repeat Customer Revenue %

*(Insert screenshot of dashboard here)*  
Download the dashboard: [`/Excel/OnlineRetail_Dashboard.xlsx`](./Excel)

## 📢 Key Insights
- **Repeat customers** are critical, contributing 60%+ of revenue → recommend loyalty programs
- **Electronics** is the highest revenue category; **Home & Kitchen** is fastest-growing
- Digital payments outperform COD → incentivize online payments
- Top 5% of customers generate ~40% of revenue → focus on high-value customer retention

## 🚀 Next Steps
- Automate ETL from SQL to Excel using Python/Power Query
- Extend dashboard to Power BI for interactive online reporting
- Build **Customer Lifetime Value (CLV)** model for strategic decision making

## 👤 Author
**Rajesh Kumar Alagesan**
- 📍 London, UK
- 🔗 [LinkedIn](https://www.linkedin.com/in/rajesh-kumar-alagesan/)
- 💻 [Portfolio](https://studio--folioforge-4hyvz.us-central1.hosted.app/)
- 🐙 [GitHub](https://github.com/DataByRajesh)
