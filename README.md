# Retail Sales Exploratory Data Analysis

A comprehensive Exploratory Data Analysis (EDA) of retail sales data to uncover patterns, trends, and insights from transaction records.

## 📊 Project Overview

This project analyzes a retail sales dataset containing 1,000 transactions to understand customer behavior, product performance, and sales patterns. The analysis helps identify key business insights that can drive strategic decisions in retail operations.

## 📁 Dataset Information

**File:** `retail_sales_dataset.csv`
- **Records:** 1,000 transactions
- **Columns:** 9 features
- **Period:** 2023 transactions

## 📈 Analysis Summary
Data Quality Assessment
- ✅ No missing values in any columns
- ✅ No duplicate records found
- ✅ Proper data types assigned
- ✅ No outliers detected in numerical features

## Key Statistics
### Numerical Features
| Metric | Age | Quantity | Price | per Unit | Total Amount |
|--------|-----|----------|-------|----------|--------------|
| Mean | 41.39 | 2.51 | 179.89 | 456.00 | $456.00 |
| Median | 42.00 | 3.00 | 50.00 | 135.00 | $135.00 |
| Std Dev | 13.68 | 1.13 | 189.68 | 559.99 | $50 |
| Range | 18-64 | 1-4 | 25-500 | 25-2000 | $559.99 |
### Categorical Features
- Gender Distribution: Female (51%), Male (49%)
- Product Categories: Clothing (35.1%), Beauty, Electronics
- Unique Customers: 1000 (each transaction from unique customer)
- Transaction Dates: 345 unique dates in 2023

## 🔍 Key Insights
### 1. Customer Demographics
- Age Distribution: Customers aged 18-64, with average age of 41 years
- Gender Balance: Nearly equal distribution between male and female customers
- Customer Base: 1000 unique customers in the dataset
### 2. Product Performance
- Category Popularity: Clothing is the most frequent purchase category
- Price Variability: Significant price range ($25-$500) across products
- Purchase Quantity: Typical purchase includes 1-4 items
### 3. Sales Patterns
- Average Transaction Value: $456 per transaction
- High Variability: Large standard deviation in total amounts indicates diverse purchasing behaviors
- Price Distribution: Bimodal distribution with peaks at lower and higher price points