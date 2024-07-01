# Sales Dashboard Project
This user story outlines the specifications for building two dashboards using Tableau to help stakeholders, including sales managers and executives, analyze sales performance and customer data.

Dashboard Purpose
The purpose of the sales dashboard is to present an overview of the sales metrics and trends to analyze year-over-year sales performance and understand sales trends.

Key Requirements

KPI Overview
Display a summary of total sales, profits, and quantity for the current year and the previous year.

Sales Trends
Present the data for each KPI on a monthly basis for both the current year and the previous year.
Identify months with the highest and lowest sales and make them easy to recognize.

Product Subcategory Comparison
Compare sales performance by different product subcategories for the current year and the previous year.
Include a comparison of sales with profit.

Weekly Trends for Sales & Profit
Present weekly sales and profit data for the current year.

Display the average weekly values.
Highlight weeks that are above and below the average to draw attention to sales & profit performance.

Data Preparation

Step 1: Import Data

Data Source: Imported data from the local drive in Tableau, which consisted of four tables: Customer, Location, Order, and Product.
Initial Selection: Chose the Order table first, then linked it with the other tables (Customer, Location, Product) using common relationships.

Step 2: Data Cleaning

Renaming Tables: Renamed the tables for clarity.

Data Type Verification: Checked and updated the data types of each column to ensure proper data handling.
Building the Dashboard

Task 1: Display a Summary of Total Sales, Profits, and Quantity for the Current Year and the Previous Year

Step 1: Create Calculated Fields

Created calculated fields for:

Current Year Sales
Previous Year Sales
Current Year Profits
Previous Year Profits
Current Year Quantity
Previous Year Quantity

Step 2: Create a Parameter

Created a parameter to represent the year and linked it to the data table.

Step 3: Visualization

BANs Chart: Used a BANs (Big Ass Numbers) chart to display a summary of total sales, profits, and quantity.
Sparkline (Line Chart): Created a sparkline to show sales trends over the selected years.

Mini-tasks involved:
Created additional calculated fields for monthly sales.
Used filters to differentiate between current and previous year data.
Designed the BANs chart to highlight the total metrics.

Task 2: Sales Trends Visualization

Step 1: Monthly Trends
Created calculated fields to aggregate sales, profits, and quantities by month.

Step 2: Visualization
Used line charts to display monthly trends for each KPI.
Highlighted months with the highest and lowest sales using color coding or annotations.

Task 3: Product Subcategory Comparison

Step 1: Data Preparation
Created calculated fields for sales and profits for each product subcategory for the current and previous years.

Step 2: Visualization
Used bar charts to represent sales performance by subcategory.
Compared sales with profits using dual-axis charts or combined bar charts.

Task 4: Weekly Trends for Sales & Profit

Step 1: Data Aggregation
Created calculated fields to aggregate sales and profits on a weekly basis.

Step 2: Calculate Averages
Calculated average weekly sales and profits.

Step 3: Visualization

Used line charts to display weekly trends.
Highlighted weeks above and below average performance using color coding or annotations.
Final Dashboard Construction

Layout and Design
Used vertical and horizontal containers to organize the layout.
Included text boxes, blank spaces, navigation elements, and images to enhance the visual appeal and usability.

Interactive Elements
Ensured the dashboard is interactive, allowing stakeholders to drill down into specific metrics and trends.

Best Practices
Applied best practices in data visualization to create an intuitive and easy-to-understand dashboard.

Conclusion
By following these steps, the sales dashboard was successfully created, meeting the specified requirements and providing valuable insights into sales performance and trends.

 
