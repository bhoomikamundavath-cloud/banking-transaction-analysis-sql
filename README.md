# Banking Transaction Analysis using SQL Server & Power BI

## Project Overview

This project analyzes banking transaction data using SQL Server and Power BI to generate actionable insights into customer behavior, transaction trends, fraud detection, loan repayment performance, and ATM usage.

The solution simulates a real-world banking Business Intelligence (BI) environment used by financial institutions for operational monitoring and strategic decision-making.

---

# Tools & Technologies

- SQL Server
- Power BI
- SQL
- Data Cleaning
- Data Modeling
- Data Visualization
- Business Intelligence

---

# Dashboard Preview

## Executive Banking Dashboard

![Dashboard](images/dashboard_preview(1).png)

---

# Database Schema

![ER Diagram](images/er_diagram(1).png)

---

# Key Analytics Performed

## Transaction Analysis
- Daily transaction volume trends
- Channel-wise transaction analysis
- Debit vs Credit transaction comparison
- Transaction amount monitoring

## Fraud Detection
- Failed transaction monitoring
- Transaction status analysis

## Loan Analytics
- Loan portfolio analysis
- Loan repayment status tracking
- Ongoing, paid and late loan monitoring

## ATM & Geographic Analytics
- ATM transaction monitoring
- Banking activity across Australian cities
- Geographic transaction distribution

## Executive Reporting
- KPI monitoring
- Interactive filtering by city, channel, and transaction type
- Business insights generation

---

# SQL Concepts Used

- JOINS
- GROUP BY
- ORDER BY
- CASE Statements
- Aggregate Functions
- Subqueries
- Data Cleaning Techniques
- Fraud Detection Queries
- KPI Reporting Queries

---

# Business Insights

- Online banking contributes the highest transaction volume.
- Failed transactions remain minimal across banking operations.
- Most loan repayments are currently ongoing.
- Digital banking channels dominate customer transactions.

---

# Project Structure

```text
BANKING_TRANSACTION_ANALYSIS/ 
│ 
├── data/ 
├── sql/ 
│ ├── 01_create_tables.sql 
│ ├── 02_insert_data.sql 
│ ├── 03_data_cleaning.sql 
│ ├── 04_transaction_analysis.sql 
│ ├── 05_fraud_detection.sql 
│ ├── 06_customer_segmentation.sql 
│ ├── 07_loan_analysis.sql 
│ └── 08_atm_usage_analysis.sql 
│ 
├── dashboard/ 
│ └──Banking_Transaction_Dashboard.pbix 
│ 
├──docs/
| └──Banking_Transaction_Database_Schema.pdf
|
├── images/ 
│ ├── dashboard_preview(1).png 
│ └── er_diagram(1).png 
│ 
└── README.md
```
---

# Future Improvements

- Real-time transaction monitoring  
- Fraud prediction using Machine Learning
- Multi-page Power BI dashboards
- Power BI Service deployment
- Customer churn analysis
---

# Author

## Bhoomika Mundavath

Master of Data Science & Artificial Intelligence  
The University of Newcastle, Australia

---

# Connect With Me

- LinkedIn: https://www.linkedin.com/in/bhoomikamundavath
- GitHub: https://github.com/bhoomikamundavath-cloud
