# Power-BI-Summative-Assessment.
This project transforms raw sales data into an interactive dashboard using Power Query, DAX, and Power BI.
# Data Cleaning & Transformation (Power Query)
 Handled Missing Values:
 Order Date: Filled 2 blanks with 01/01/1900.
 Customer Name, Region, Product: Filled blanks with "Unknown".
 Unit Price: Found 1 blank using Sales Price / Quantity.
 Sales Price: Found 3 blanks using Quantity * Unit Price.
 Cost: Found 1 blank using Sales - Profit.
 Profit: Found 2 blanks using Sales - Cost.
 Data Cleanup: Removed duplicate rows and standardized all column formats.
 # 🧮 DAX Calculations
 Calculated Table: East Region Order (Filters transactions for the East region).
 Calculated Column: Profit Cost Difference (Tracks the gap between profit and cost per row).
 Calculated Measure: Total Profit (Tracks cumulative profits across the dashboard).
# 📊 Dashboards & Visuals (Power BI)
 # Key Visuals:
 Pie chart for regional order distribution.
 Column chart showing the top 5 trending products.
 Line chart tracking profit trends over time.
 # Report Pages:
 Executive Sales Analysis: High-level company performance overview.
 Product Analysis: Deep dive into specific item performance.
 Region-Wise Sales: Geographic sales distribution mapping.
 Insights & Recommendations: Simple, data-driven action plans.
