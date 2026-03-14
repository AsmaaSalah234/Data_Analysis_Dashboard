# Sales Performance Analysis – Power BI Project
## Project Overview

This Power BI dashboard provides a comprehensive analysis of sales performance across different products, categories, countries, and time periods.
The objective of this project is to transform raw sales data into meaningful insights that help understand sales trends, identify top-performing products, and analyze category performance.

The dashboard enables decision-makers to explore sales distribution, monitor performance over time, and identify opportunities to improve revenue and product strategy.

## Business Questions

-What is the total sales performance across the dataset?

-How have sales changed over time?

-Which products generate the highest revenue?

-Which product categories contribute the most to total sales?

-How does sales performance vary across different countries?

-How can the company improve sales strategy based on product and category performance?

## Process
## Data Cleaning & Preparation

The dataset was cleaned and prepared using Power Query before performing the analysis.

Steps performed:

• Handled missing values by replacing Null values using COALESCE to ensure data completeness.

• Merged First Name and Last Name columns into a single column using the Merge Columns feature in Power Query.

• Verified and cleaned the dataset to ensure consistency before starting the analysis.

## Key Metrics

• Total Orders: 100 orders recorded in the dataset.

• Total Customers: 12 unique customers.

• Total Sales: Approximately $1M in revenue generated.

These KPIs provide a quick overview of overall business performance.

# Data Analysis & Visualization
# Sales Over Time (Line Chart)

This visualization shows how sales evolved across different time periods.

Insights:
• Sales experienced noticeable fluctuations across the timeline.
• There was a strong peak around mid-2024, indicating a high-performing sales period.
• After that peak, sales dropped significantly before gradually stabilizing and increasing again toward 2026.

This trend suggests possible seasonality or promotional impacts during certain periods.

## Sales by Product (Bar Chart)

This chart highlights the top-selling products based on total revenue.

Key insights:

• ThinkPad X1 is the top-performing product generating approximately $0.36M in sales.

• Dell XPS 15 follows with around $0.25M in sales.

• Smartphones such as iPhone 16 and Galaxy S24 also contribute significantly to total revenue.

• Some products such as MacBook Air M4 and Galaxy Tab S10 show relatively lower sales performance.

This indicates that premium laptops dominate the sales distribution.

## Sales by Category (Donut Chart)

This visualization shows how sales are distributed across product categories.

Insights:

• Laptop category dominates sales, contributing more than 50% of total revenue (~751K).

• Smartphones represent the second-largest share (~293K).

• Tablets and Smart Home devices contribute smaller portions of revenue.

• Accessories represent the smallest sales segment.

This suggests that the company's core revenue is heavily dependent on laptop products.

## Interactive Filters (Slicers)

The dashboard includes interactive filters that allow users to explore data dynamically.

Filters available:

• Date Range Filter – analyze sales for specific time periods.
• Country Filter – compare performance between China, Germany, India, and the United States.
• Product Category Filter – explore performance by category.

These filters make the dashboard interactive and flexible for deeper analysis.

# Sales Performance Insights
1. Overall Sales Performance

The business generated approximately $1M in total sales from 100 orders and 12 customers, indicating that each customer contributes significant purchase value.

2. Product Performance

Laptop products dominate the sales rankings.
ThinkPad X1 and Dell XPS 15 together represent a large portion of total revenue.

This indicates strong demand for high-performance laptops.

3. Category Contribution

Laptop products generate more than half of the company’s revenue, making them the core driver of the business.

Meanwhile, categories like accessories and smart home devices have relatively low contribution.
4. Sales Trend Over Time

Sales trends show periods of strong growth followed by declines and recovery phases.

The peak around mid-2024 suggests either:

• successful promotions
• high market demand
• product launches

Understanding these drivers could help replicate similar success in future periods.

# Actionable Recommendations
## Focus on Top-Selling Products

Since ThinkPad X1 and Dell XPS 15 generate the highest revenue, the company should prioritize inventory and marketing for these products.

Strengthen Laptop Category Strategy

Because laptops contribute the majority of revenue, investing in this category could maximize growth.

Possible actions:

• launch new laptop models
• offer bundle deals with accessories
• improve marketing campaigns

## Improve Low-Performing Categories

Accessories and smart home products generate relatively low sales.

Potential improvements:

• create bundle offers with laptops
• run promotional campaigns
• adjust pricing strategies

Analyze Sales Peaks

The sales spike in mid-2024 should be investigated.

Possible causes:

• promotional campaigns
• seasonal demand
• product launches

Understanding this can help replicate high-performance periods.

## Expand High-Demand Markets

Using the country filters, the company can identify regions with strong demand and prioritize marketing efforts there.

# Tools Used

• Power BI – Data Visualization & Dashboard Development
• Power Query – Data Cleaning & Transformation
• DAX – Calculations and KPIs
