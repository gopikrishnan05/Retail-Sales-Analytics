# Retail Sales Performance Analysis

## Project Overview

This project focuses on analysing retail sales data to identify revenue drivers, understand customer purchasing patterns, evaluate product category performance and uncover seasonal sales trends.

The objective is to transform raw retail data into meaningful business insights using Python, SQL and Power BI, helping business stakeholders make data-driven decisions.

## Business Objectives

- Analyse overall retail sales performance.
- Identify top-performing and underperforming product categories.
- Understand purchasing patterns across gender and age groups.
- Evaluate seasonal sales performance.
- Analyse high-value transactions and their contribution to total revenue.
- Provide actionable business recommendations.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data cleaning and exploratory data analysis |
| Pandas | Data manipulation and analysis |
| SQL | Business analysis and data aggregation |
| Power BI | Interactive dashboard development |
| DAX | KPI calculations and measures |

## Dataset Overview

The project uses a retail sales dataset obtained from Kaggle.

- **Total Records:** 5,000
- **Total Columns:** 11
- **Missing Values:** 0
- **Duplicate Records:** 0

### Dataset Columns

| Column | Description |
|---|---|
| CustomerID | Customer identifier |
| Age | Customer age |
| Gender | Customer gender |
| Category | Product category |
| ItemPurchased | Purchased product |
| Amount | Transaction amount |
| Season | Purchase season |
| PaymentMethod | Payment method |
| ItemRating | Product rating |
| DiscountApplied(%) | Discount percentage |
| PreviousPurchases | Previous purchase count |

## Project Workflow

### 1. Data Understanding
- Explored dataset structure and dimensions.
- Identified numerical and categorical variables.
- Reviewed statistical summaries and data distributions.

### 2. Data Cleaning
- Checked missing values and duplicate records.
- Verified data types.
- Identified potential outliers using the IQR method.
- Retained potential genuine high-value transactions instead of removing them without business justification.

### 3. Exploratory Data Analysis (EDA)
Performed analysis on:
- Category-wise revenue.
- Product-wise revenue.
- Gender-wise purchasing behaviour.
- Age-group sales performance.
- Seasonal sales trends.
- Discount distribution.
- Customer ratings.
- High-value transactions.

### 4. SQL Business Analysis
Used SQL queries to perform:
- Category-wise revenue aggregation.
- Top-performing category identification.
- Gender-wise sales analysis.
- Seasonal sales analysis.
- Conditional transaction classification.
- High-value revenue contribution analysis.

SQL concepts used:
`SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, `HAVING`, aggregate functions and `CASE WHEN`.

### 5. Power BI Dashboard

Developed an interactive dashboard featuring:

**Key Performance Indicators**
- Total Revenue
- Total Transactions
- Average Transaction Value
- Average Customer Rating
- High-Value Transactions
- Average Discount

**Dashboard Visualisations**
- Category-wise Revenue Performance
- Gender-wise Revenue Analysis
- Seasonal Sales Performance
- Age-group Revenue Analysis
- High-Value vs Regular Transaction Distribution
- Season-wise Category Revenue Matrix

**Interactive Filters**
- Season
- Category
- Gender
- Payment Method

## Key Business Insights

### 1. Electronics Dominates Revenue
- Generated revenue of ₹895,402.35.
- Accounted for approximately 62.82% of total revenue.
- Recorded 507 transactions.
- Average transaction value was approximately ₹1,766.08.

**Insight:** Electronics is the primary revenue contributor despite having a relatively low transaction count.

### 2. Gender-wise Revenue Analysis
- Male customer transactions: 2,496.
- Female customer transactions: 2,504.
- Male revenue: ₹1,149,713.96.
- Female revenue: ₹275,738.65.

**Insight:** Male transactions contributed significantly higher aggregate revenue, despite similar transaction volumes across genders.

### 3. High-Value Transaction Analysis

Transactions above ₹1,000 were classified as high-value transactions.

- High-value transactions: 415 (8.3%).
- Regular transactions: 4,585 (91.7%).
- High-value transaction revenue: ₹829,829.85.
- High-value revenue contribution: 58.22%.

**Insight:** A relatively small proportion of transactions contributes a significant share of total revenue.

### 4. Age-group Analysis
- Age group 40–49 generated the highest total revenue of ₹302,523.03.
- Age group 30–39 recorded the highest average transaction value.

**Insight:** Different age groups contribute to revenue in different ways.

### 5. Seasonal Performance
- Spring recorded the highest transaction count (1,300).
- Spring recorded the highest average transaction value (approximately ₹289.25).
- Electronics remained the highest-revenue category across all four seasons.

**Insight:** Seasonal purchasing patterns can help businesses understand demand variation and plan inventory.

## Business Recommendations

1. **Revenue Diversification:** Reduce excessive dependence on Electronics by identifying opportunities to improve revenue from other categories.

2. **High-Value Transaction Monitoring:** Monitor high-value product sales and maintain appropriate inventory availability.

3. **Seasonal Planning:** Use seasonal sales patterns to support inventory and promotional planning.

4. **Customer Segmentation:** Analyse product preferences across age and gender segments to develop more relevant marketing strategies.

## Project Limitations

The dataset does not contain certain business-critical fields:

- Transaction dates: Actual monthly and yearly sales growth cannot be calculated.
- Product cost and profit: Profitability cannot be evaluated.
- Location: Regional sales performance cannot be analysed.
- Marketing channels: Advertising channel effectiveness cannot be measured.
- Quantity: Actual units sold cannot be determined.
- Customer purchase history: Customer retention and repeat purchase behaviour cannot be reliably evaluated.

These limitations were considered while interpreting the results and preparing recommendations.

## Project Outcome

This project demonstrates an end-to-end data analytics workflow, from data cleaning and exploratory analysis to SQL-based business analysis and interactive Power BI dashboard development.

It highlights the ability to transform raw data into actionable business insights and communicate findings to stakeholders.

---

**Tools:** Python | Pandas | SQL | Power BI | DAX

**Project Type:** End-to-End Data Analytics Project

**Author:** [Gopi Krishnan G]


