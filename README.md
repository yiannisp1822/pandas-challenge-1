# pandas-challenge-1
# Yiannis Pagkalos

# Wholesale Data Analysis

## Project Overview

This project involves analyzing wholesale data to derive insights and make data-driven decisions. The analysis focuses on key metrics such as total units purchased, total shipping price, total revenue, and total profit. The goal is to identify top clients, understand product performance, and optimize costs.

## Data

The dataset contains information on client orders, including details such as client ID, order date, item ID, category, unit price, unit cost, unit weight, quantity, and line number. The dataset is used to calculate various metrics and perform the analysis.

## Key Metrics

- **Total Units Purchased**: The total number of units purchased by clients.
- **Total Shipping Price**: The total cost incurred for shipping the products.
- **Total Revenue**: The total revenue generated from sales.
- **Total Profit**: The total profit after accounting for costs and shipping expenses.

## Analysis Steps

1. **Data Cleaning and Preparation**:
    - Load the dataset into a DataFrame.
    - Rename columns for better readability.
    - Identify and handle missing values if any.

2. **Calculating Shipping Price**:
    - Calculate the shipping price based on unit weight and quantity.
    - Apply different shipping rates for items with weight greater than 50 and less than or equal to 50.

3. **Aggregating Metrics for Top Clients**:
    - Identify the top 5 clients based on total units purchased.
    - Calculate total units purchased, total shipping price, total revenue, and total profit for these clients.

4. **Formatting Monetary Values**:
    - Format monetary values to represent millions of dollars for better readability.

## Conclusions

Based on the data analysis, the following conclusions were drawn:

1. **Summary of Key Metrics**:
    - The top 5 clients contributed significantly to the total revenue and profit with the top clinet accounting for more that 50% of the total revenue
    - Shipping costs were substantial, highlighting the need for cost optimization.

2. **Top Clients**:
    - These clients placed large orders consistently, indicating high satisfaction levels.

3. **Product Performance**:
    - the highest revenue category was consumables and within that bathroom supplies
    - Lightweight products had lower shipping costs and contributed positively to profit margins.

4. **Cost Analysis**:
    - There was a correlation between unit weight and shipping costs.
    - Implementing bulk shipping options could help reduce costs.

6. **Recommendations**:
    - Strengthen relationships with top clients through personalized services.
    - Explore bulk shipping options to reduce costs.
    - Monitor product performance and adjust strategies based on demand trends.
    - Conduct further analysis on client preferences for cross-selling and upselling opportunities.
    - increase total order quanity from the top 2/3/4/ clients

