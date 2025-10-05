# Retail Sales Analysis & Customer Insights

## Project Overview

This project focuses on analyzing a retail sales dataset to uncover patterns in customer behavior, product preferences, payment methods, and sales trends. The goal is to provide actionable insights that can help businesses optimize marketing strategies, enhance customer targeting, and maximize revenue.

!(https://github.com/sshankt/Customer-Shopping-Dataset-Analysis/blob/main/Man-and-woman-shopping-Shutterstock-984x500-1.webp)
**Dataset Columns:**

* gender
* age
* category
* quantity
* price
* payment_method
* invoice_date
* shopping_mall
* year
* month
* day
* total_amount

## Objective

* Understand the demographics of customers.
* Analyze product category popularity and revenue contribution.
* Explore payment method preferences.
* Identify time-based shopping trends (daily, monthly).
* Provide actionable insights for business strategy and decision making.

## Tools & Libraries

* Python 3.x
* Pandas – Data manipulation and analysis
* Matplotlib – Data visualization
* Seaborn – Advanced visualizations

## Exploratory Data Analysis (EDA)

### 1. Customer Demographics

* Gender Distribution: Most customers are women.
* Age Distribution: Majority of customers are 25–35 years old, with 30–40 contributing the most revenue.

*Visualizations:* Count plot for gender, histogram and bar plots for age vs total sales.

### 2. Product Analysis

* Popular Categories: Clothing and Cosmetics.
* Revenue Contribution: Electronics generates high revenue.
* Average Price per Category: Accessories have the lowest, Electronics the highest.

*Visualizations:* Count plots for category distribution, bar plots for total sales by category.

### 3. Payment Method Analysis

* Most Used Methods: Cash and Credit Card.
* Revenue by Payment Method: Cash and Credit Card generate the most revenue.

*Visualizations:* Count plot for payment methods, bar plot for total sales by payment method.

### 4. Shopping Mall Analysis

* Top Malls by Transactions: Phoenix Mall and Select City Walk.
* Top Malls by Revenue: Phoenix Mall has the highest total sales; Select City Walk has higher average spend.

*Visualizations:* Count plot for mall-wise transactions, bar plot for total sales by mall.

### 5. Time-Based Analysis

* Monthly Trend: Sales peak in December.
* Daily Trend: Weekends have the highest sales.

*Visualizations:* Line plot for monthly sales trend, line plot for daily sales trend.

### 6. Quantity & Price Analysis

* Most purchases contain 1–3 items.
* Majority of transactions are in moderate price range.

*Visualizations:* Histograms for quantity and price distribution.

### 7. Correlation Analysis

* Strong positive correlation between total_amount, price, and quantity.
* Weak positive correlation between age and total_amount.

*Visualizations:* Heatmap of numeric column correlations.

## Key Insights

* Target marketing campaigns on women aged 25–35.
* Promote Clothing and Cosmetics, upsell Electronics.
* Ensure smooth Cash and Credit Card payment options.
* Plan promotions for weekends and festive seasons.

## Conclusion

The analysis highlights clear trends in customer demographics, product preferences, and shopping behavior. Businesses can use these insights to target the right customers, optimize product offerings, and maximize revenue.

Most customers are women aged 25–35, shopping mainly for Clothing and Cosmetics. Cash and Credit Card are the preferred payment methods, with weekends and December being peak sales periods.
