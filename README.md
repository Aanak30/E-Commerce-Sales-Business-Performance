# End-to-End E-Commerce Sales & Business Analytics

An end-to-end data analytics project that transforms raw e-commerce data into meaningful business insights using **Excel, PostgreSQL, SQL, and Power BI**.

The project follows a complete analytics workflow, from data preparation and database ingestion to SQL-based analysis, analytical views, and interactive business intelligence dashboards.

## Project Overview

E-commerce businesses generate large amounts of data across sales, customers, products, orders, deliveries, and customer reviews. Analyzing these datasets together helps businesses understand revenue performance, customer behavior, product performance, and operational efficiency.

This project uses a structured analytics workflow to prepare, query, analyze, and visualize e-commerce data, turning raw records into information that supports data-driven decision-making.

## Project Objectives

- Prepare and validate raw data using Excel.
- Import structured datasets into PostgreSQL.
- Use SQL to query, join, aggregate, and analyze business data.
- Create analytical views for reusable reporting, where applicable.
- Analyze revenue, orders, customers, categories, delivery performance, and reviews.
- Connect the analytical data to Power BI.
- Build an interactive, multi-page dashboard to communicate business insights.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Excel | Data inspection, initial cleaning, validation, and exploratory analysis |
| PostgreSQL | Database storage and management |
| SQL Views | Reusable analytical datasets for reporting, where implemented |
| Power BI | Interactive dashboards, KPIs, and business visualizations |
| DAX | Measures and KPI calculations, where implemented |
| Power Query | Data transformation and preparation, where implemented |

## End-to-End Project Workflow

### 1. Data Preparation — Excel

- Inspected the raw datasets to understand their structure and fields.
- Checked for missing values, duplicate records, inconsistent formats, and data quality issues.
- Prepared data for database ingestion where necessary.
- Reviewed key business fields such as order dates, customer identifiers, product categories, revenue, delivery dates, and review scores.

### 2. Database Ingestion — PostgreSQL

- Created a PostgreSQL database for the e-commerce datasets.
- Imported the relevant CSV files into database tables.
- Checked table structures, data types, and record counts.
- Validated key fields and relationships between the datasets.

### 3. SQL Analysis — PostgreSQL

Used SQL to explore the data and answer business questions through queries involving:

- SELECT, WHERE, ORDER BY, and DISTINCT
- GROUP BY and aggregate functions
- JOINs across related tables
- CASE expressions and conditional aggregation
- Subqueries and Common Table Expressions (CTEs), where applicable
- Date-based analysis and time-period comparisons
- Revenue, order volume, customer, category, and delivery analysis

### 4. Analytical Views

Created reusable SQL views where appropriate to organize business metrics and simplify downstream reporting.

Potential analytical areas include:

- Sales and revenue performance
- Category-level sales
- Customer and geographic analysis
- Delivery performance
- Customer review and rating analysis

### 5. Power BI Integration

Connected Power BI to the analytical data and developed interactive reports to monitor key performance indicators and explore business performance.

The report design focuses on clear visual hierarchy, consistent formatting, relevant metrics, and easy navigation across six report pages.

## Dashboard Pages

### Page 1 — Executive Overview

Provides a high-level summary of business performance through total revenue, total orders, total customers, average order value, monthly orders, revenue trends, top categories by revenue, and order status distribution.

**Business question:** What does overall e-commerce performance look like?
![E-Commerce Sales Dashboard](/Sceenshorts/Overview.png)

### Page 2 — Sales Trend Analysis

Examines revenue and order trends over time, including yearly comparisons of revenue, orders, and average order value across categories.

**Business question:** How has sales performance changed over time?
![E-Commerce Sales Dashboard](/screenshort/Sales Trend.png)

### Page 3 — Category & Product Analysis

Compares product categories using revenue, order volume, average order value, customer ratings, and category revenue share.

**Business question:** Which categories contribute most to business performance?

![E-Commerce Sales Dashboard](/screenshort/Category.png)


### Page 4 — Customer Analysis

Explores geographic sales patterns across customer states and cities, along with category-level performance across locations.

**Business question:** Where are customers located, and which geographic areas generate the most revenue?
![E-Commerce Sales Dashboard](/screenshort/Customers.png)


### Page 5 — Delivery & Logistics

Analyzes average delivery duration, late orders, on-time delivery performance, and delivery patterns across geographic segments.

**Business question:** Where can delivery operations be improved?
![E-Commerce Sales Dashboard](/screenshort/Review.png)

### Page 6 — Customer Reviews

Examines rating distribution, average ratings, category-level ratings, and the relationship between review scores and delivery performance.

**Business question:** What does customer feedback reveal about the customer experience

![E-Commerce Sales Dashboard](/screenshort/Review.png)

## Key Business Metrics

| Metric | Business purpose |
|---|---|
| Total Revenue | Measures sales value |
| Total Orders | Measures order volume |
| Total Customers | Tracks customer reach |
| Average Order Value (AOV) | Measures average revenue per order |
| Revenue by Category | Identifies important product segments |
| On-Time Delivery % | Measures delivery reliability |
| Late Orders | Tracks delayed orders |
| Average Rating | Summarizes customer feedback |

## Key Business Questions

This project is designed to investigate questions such as:

1. Which categories generate the highest revenue?
2. How do monthly and yearly sales trends change over time?
3. Which customer states contribute most to revenue?
4. How does average order value vary across categories?
5. How many orders are delivered late, and what is the on-time delivery rate?
6. How are customer ratings distributed across the business?
7. Do late deliveries coincide with lower customer ratings?

## Key Findings

Add three to five verified findings from the completed analysis here.

For each finding, include:
- The business question
- The result supported by SQL or Power BI
- The relevant metric or comparison
- A brief business implication


#
