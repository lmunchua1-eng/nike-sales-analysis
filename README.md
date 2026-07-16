# nike-sales-analysis
Exploratory analysis of Nike retail sales using Python, Pandas, and Matplotib.
# Nike Sales Analysis

## Project Overview

This project analyzes a Nike retail sales dataset using Python to identify trends in product performance, revenue, profit, regional sales, sales channels, and monthly performance.

The project follows a complete data analytics workflow, including data inspection, cleaning, exploratory data analysis, visualization, and business recommendations.

## Objective

The objective of this project is to transform raw retail sales data into meaningful business insights that could support product, marketing, inventory, and sales decisions.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Data Cleaning

The dataset was cleaned by:

- Removing the `Discount_Applied` column because most values were missing
- Removing records with missing `Units_Sold`, `MRP`, or `Order_Date`
- Replacing missing product sizes with `Unknown`
- Converting `Order_Date` into a datetime format
- Checking for duplicate and invalid records

## Analysis Performed

- Total revenue and profit
- Number of unique products
- Revenue by product line
- Revenue by region
- Profit by product line
- Sales channel performance
- Top-performing products
- Monthly revenue trends

## Key Findings

- Monthly revenue fluctuated considerably throughout the analysis period.
- Revenue performance was generally stronger during late 2024 and early 2025 than during earlier periods.
- Certain product lines, regions, and sales channels contributed more revenue and profit than others.
- The monthly fluctuations suggest that seasonality, promotions, or changes in product demand may influence sales performance.

## Recommendations

- Prioritize inventory and marketing support for the strongest product lines.
- Continue investing in regions and sales channels with strong revenue performance.
- Investigate lower-performing products to identify pricing, marketing, or inventory issues.
- Monitor monthly performance to prepare for periods of increased or reduced demand.
- Examine promotional and product-launch data to better explain large monthly revenue fluctuations.

## Files

- `Nike_Sales_Analysis.ipynb` — complete analysis, code, visualizations, insights, and recommendations
- `Nike_Sales_Uncleaned.csv` — original dataset used in the project

## How to View the Project

Open `Nike_Sales_Analysis.ipynb` directly in this repository to view the full analysis and its visualizations.
