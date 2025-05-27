# Overview
# Toy Store KPI Report - Power BI Project

## Project Overview
I created an interactive Power BI dashboard to analyze sales data for Maven Toys, a fictional toy store chain in Mexico. The report helps leadership monitor business performance from January 2022 through September 2023.

## Files
- Sales data: Transaction records
- Products: Product details (ID, name, category, cost, price)
- Stores: Store locations (ID, name, city, location, opening date)
- Calendar: Date table for time analysis

## Work Completed

1. DATA PREPARATION
- Imported all CSV files into Power BI
- Verified no missing values
- Confirmed correct data types
- Identified key fields:
  - Primary keys: ProductID, StoreID, Date
  - Foreign keys: Sales table connections
- Added calculated date columns to Calendar table

2. DATA MODELING
- Built star schema with Sales as central fact table
- Created relationships between:
  - Sales → Products
  - Sales → Stores
  - Sales → Calendar
- Hid technical fields from report view

3. CALCULATIONS
Created these measures:
- Total Orders (count of transactions)
- Total Revenue (sum of sales)
- Total Profit (revenue minus costs)
Bonus: Also created measures that calculate directly without using intermediate columns

4. VISUALIZATIONS
Built these report elements:
- KPI cards showing current month values with trends
- Store location filter slicer
- Bar chart: Orders by product category
- Line chart: Revenue over time (by month/week)
Formatted all elements for clean, professional look

## How to Use
1. Filter by store location using the slicer
2. Hover over charts for details
3. Click to drill into time periods

## Skills Demonstrated
- Power Query data preparation
- Data modeling (star schema)
- DAX formula writing
- Effective visualization design

## Files Included
- Power BI file (.pbix)
- Original CSV data files

This project gave me hands-on experience with the full Power BI workflow from data loading through to interactive reporting. I'm open to feedback and suggestions for improvement!
## Data Source
I got this dataset from Maven Analytics Data Playground
[download here](https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=mexico%20)
## Dashboard
[Mexico Toy Sales]![Blue](https://github.com/user-attachments/assets/9b91e508-5eca-4353-a2c8-3e63bdbaae53)

