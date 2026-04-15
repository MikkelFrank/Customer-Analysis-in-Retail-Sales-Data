# Customer Analysis in Retail Sales Data

## Project Overview

This project analyzes customer behavior within a retail sales dataset. The focus is on understanding customer value, purchasing patterns, and revenue distribution using SQL and Python.

---

## Objective

The goal of this project is to:

* Identify high-value customers
* Analyze customer concentration
* Understand customer segmentation
* Evaluate customer retention (repeat vs one-time buyers)
* Derive actionable business insights

---

## Tools & Technologies

* Python (Pandas)
* SQL (SQLite)
* Matplotlib
* Jupyter Notebook (VS Code)

---

## Project Structure

```
customer_analysis_project/
├── data/
│   └── train.csv
├── customer_analysis_project.ipynb
```

---

## Process

### 1. Data Cleaning

* Standardized column names for consistency
* Converted date columns to datetime format
* Checked for missing values
* Removed duplicate rows

---

### 2. Customer Analysis (SQL)

The following analyses were performed:

* Top customers by total sales
* Customer concentration (Top 5 contribution to total sales)
* Sales by customer segment
* Average order value per customer
* Repeat vs one-time customers

---

### 3. Data Visualization

The following visualizations were created:

* Top 10 customers by total sales (bar chart)
* Total sales by customer segment (bar chart)
* Repeat vs one-time customers (bar chart)

---

## Key Insights

* The top 5 customers contribute approximately 3.9% of total sales, indicating that revenue is widely distributed across the customer base.

* The vast majority of customers are repeat customers (~98%), suggesting strong customer retention and consistent purchasing behavior.

* The Consumer segment generates the highest total sales, followed by Corporate and Home Office.

* Sales are not concentrated among a small number of customers, indicating a diversified customer portfolio.

* The combination of high retention and low customer concentration suggests a stable and resilient revenue structure.

---

## Conclusion

This analysis demonstrates how customer data can be used to evaluate business stability, identify revenue patterns, and assess customer behavior. The results indicate a diversified and retention-driven customer base.
