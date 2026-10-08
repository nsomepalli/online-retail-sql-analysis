# Online Retail Sales Analysis (SQL)

## Overview
Analyzed UK online retail transactions using SQL (SQLite) to understand
revenue drivers, customer concentration, and international markets.

## Dataset
Online Retail dataset from Kaggle (~541,909 transactions, Dec 2010 to Dec 2011).

## Data Cleaning
- Removed cancelled orders (invoices starting with "C")
- Removed invalid quantities and prices
- Excluded non-product entries (postage, manual adjustments, fees)
- Excluded two bulk orders (74K and 81K units) that were cancelled after the fact

## Key Findings
- Total revenue of about £10.0M after cleaning
- UK accounted for ~85% of revenue
- Top 10 products made up only ~8% of revenue (diversified product mix)
- Top 10 customers made up ~14% of revenue
- Largest international markets: Netherlands, EIRE, Germany, France
- Cancellation rate: 1.7% of order lines

## SQL Skills Used
Aggregations, GROUP BY, CASE statements, views, filtering, DISTINCT

## Files
- `online_retail_analysis.sql`: all queries