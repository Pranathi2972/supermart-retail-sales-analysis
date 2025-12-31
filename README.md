# Supermart Grocery Sales Analysis

## Overview
This project focuses on analyzing grocery sales data from a Supermart to understand sales performance, profit trends, and the effect of discounts on profitability. The goal is to explore retail sales patterns and extract insights that can help in better business decision-making.

---

## Objective
The main objectives of this project are:
- To analyze overall sales and profit distribution  
- To understand how discounts affect profitability  
- To identify high-performing product categories and regions  
- To study sales trends over time  

---

## Dataset
- **Source:** Supermart Grocery Sales Dataset  
- **Records:** ~10,000 sales transactions  
- **Key Columns:**
  - Order ID  
  - Customer Name  
  - Category & Sub-Category  
  - City, State, and Region  
  - Sales  
  - Discount  
  - Profit  
  - Order Date  

The dataset represents real-world retail transactions and required basic preprocessing and feature extraction.

---

## Approach
The project was carried out using the following steps:
1. Loaded and inspected the dataset  
2. Cleaned the data and handled data types  
3. Extracted date-related features  
4. Performed exploratory data analysis using visualizations  
5. Analyzed relationships between sales, profit, and discount  
6. Interpreted insights from a business perspective  

---

## Analysis & Insights
- Sales values vary significantly across transactions  
- Certain product categories contribute more to total revenue  
- Higher discounts do not always result in higher profits  
- Sales show noticeable trends over time, indicating seasonality  

---

## How to Run
```bash
pip install -r requirements.txt
python supermart_sales_analysis.py
