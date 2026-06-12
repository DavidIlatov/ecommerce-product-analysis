# E-Commerce Customer Analytics

## Project Overview

This project analyzes customer purchasing behavior using an e-commerce transaction dataset.

The main objective is to identify high-value customers, understand purchasing patterns, and detect customers at risk of churn.

The project follows a complete analytics workflow including data assessment, data preparation, SQL analysis, business KPI development, and dashboard visualization in Power BI.

---

## Business Problem

E-commerce companies need to understand customer behavior in order to:

- Increase customer retention
- Identify high-value customers
- Detect customers at risk of churn
- Improve marketing effectiveness
- Increase revenue through customer segmentation

This project aims to answer these business questions using transaction-level data.

---

## Dataset

Online Retail Dataset

Dataset characteristics:

- 541,910 transaction records
- 4,373 unique customers
- 38 countries
- Transaction period: December 2010 – September 2011

Each row represents a product purchased within an invoice.

Example:

Invoice No: 536365

Products:
- White Hanging Heart T-Light Holder
- White Metal Lantern
- Cream Cupid Hearts Coat Hanger

All belong to the same order.

---

## Initial Data Assessment

The following transaction patterns were identified during the initial data profiling phase and require further business validation:

- 10,624 records with Quantity <= 0
- 2,517 records with UnitPrice <= 0
- 135,081 records with missing CustomerID

Initial hypotheses:

- Negative quantities may represent product returns or cancelled orders.
- Non-positive unit prices may represent accounting adjustments, credits, or promotional items.
- Missing CustomerID values may represent anonymous transactions.

At this stage, these records are not automatically treated as data quality issues and will be investigated before any filtering decisions are made.

---

## Key Business Questions

1. Who are the highest-value customers?
2. Which customers generate the highest revenue?
3. What is the repeat purchase rate?
4. Which customers are at risk of churn?
5. Which countries generate the highest revenue?
6. How is revenue distributed across customer segments?
7. What customer behaviors are associated with higher spending?

---

## KPIs

The project will focus on the following business KPIs:

- Total Revenue
- Number of Customers
- Number of Orders
- Average Order Value (AOV)
- Revenue per Customer
- Repeat Purchase Rate
- Customer Lifetime Value (CLV)
- Churn Rate

---

## Tools

- SQL Server
- SQL Server Management Studio (SSMS)
- Power BI
- GitHub

---

## Project Workflow

1. Data Understanding
2. Data Assessment
3. Data Preparation
4. SQL Analysis
5. KPI Development
6. Power BI Dashboard
7. Business Insights & Recommendations

---

## Expected Deliverables

### SQL

- Data profiling queries
- Customer analysis
- Revenue analysis
- Customer segmentation
- Churn identification

### Power BI

- Executive Dashboard
- Customer Analytics Dashboard
- Churn Analysis Dashboard
- Geographic Analysis Dashboard

### Business Insights

Actionable recommendations based on customer purchasing behavior and revenue contribution.


