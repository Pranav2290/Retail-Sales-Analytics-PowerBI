# Retail-Sales-Analytics-PowerBI
## 🔍 Overview

This project analyzes retail sales data to uncover key drivers of profitability and loss using Power BI.
Despite strong sales performance, businesses often struggle with hidden losses caused by discounting strategies and product-level inefficiencies.
This dashboard provides a data-driven approach to identify these issues and support better decision-making.

## 🎯 Problem Statement
The business faced the following challenges:
- High sales but inconsistent profitability
- Lack of visibility into loss-making products and regions
- Unclear impact of discount strategies on profit

## 🛠️ Solution Approach
### 🔹Data Preparation
- Cleaned and transformed ~10,000+ transaction records using Power Query
- Created derived features:
  - Profit Category (Profit/Loss)
  - Discount Category (Low/Medium/High)
  - Profit Margin & Delivery Days
 

### 🔹Data Modeling
- Designed a star schema:
  - Fact table → Transactions
  - Dimension tables → Product, Customer, Location, Date
- Created surrogate keys for proper relationships

### 🔹DAX & KPIs
Developed key business metrics:
- Total Sales, Total Profit, Total Orders
- Profit Margin %
- Loss Orders & Loss %
- Discount Impact Metrics

## 📊 Dashboard Pages
