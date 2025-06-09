# E-Commerce-Sales-Performance-Analysis
The project utilizes Tableau to create an interactive dashboard and storyboard to analyze a comprehensive e-commerce sales dataset, providing insights into sales performance, profitability, and operational efficiency.
# Dataset
- The dataset comprises e-commerce sales orders with 24 columns, capturing:
- Identifiers: Order ID, Customer ID
- Temporal Data: Order Date, Ship Date, Order Year/Month
- Demographic Data: City, State, Country, Region
- Customer Data: Customer Name, Segment
- Product Data: Product ID, Category, Sub-Category, Product Name
- Financial Metrics: Sales, Profit, Discount, Shipping Cost
- Operational Metrics: Ship Mode, Order Priority, Delivery Days
- This rich dataset supports geographic segmentation, product performance analysis, and supply chain optimization.
# Visualizations
Tableau Dashboard (CA-2)
- The dashboard offers an interactive interface with the following visualizations:
- Geographic Sales Map:
  - Displays total sales by region with a tooltip showing the highest sold category.
  - Acts as a filter for other visualizations.
- Highest Sold Category Bar Graph:
  - Shows sales by sub-category, color-coded for clarity.
- Profit and Discount Trends:
  - Dual-axis line graph tracking profit and discount over time.
- Sales by Ship Mode Pie Chart:
  - Illustrates sales distribution across shipping modes, color-coded by market.
- Sales by Market Tree Map:
  - Visualizes market performance with size and color differentiation.
- Discounted Sales Bar Graph:
  - Displays sales with discounts using a calculated field, color-coded by category.
- Date Range Parameter:
  - Enables filtering by specific time periods.
# Sales Performance Storyboard (CA-4)
The storyboard narrates key performance indicators (KPIs) with insights:
- Primary KPI: Total Sales
- Supporting KPIs:
  - Sales by Country: U.S. leads, Laos lags (world map).
  - Sales by Category: Phones (Technology) are top-sellers, Labels (Office Supplies) are lowest (bar graph).
  - Sales by Ship Mode: Standard Class dominates (pie chart).
  - Profit and Discount Trends: Profit peaks in September 2015 ($67,409), lowest in July 2012 ($3,928); discounts fluctuate similarly (line graph).
  - Sales by Market: Asia Pacific ($4,035,462), Europe ($3,281,445), USCA ($2,358,033), LATAM ($2,159,583), Africa ($781,499) (tree map).
  - Discounted Sales: Chairs (Furniture) have the highest discounted sales, Labels the lowest (bar graph).
# Key Insights
- Geographic Performance: The U.S. drives the highest sales, while Laos contributes the least, guiding market expansion strategies.
- Product Trends: Phones are the top-performing product, while Labels underperform, suggesting inventory optimization.
- Shipping Preferences: Standard Class is the preferred shipping mode, indicating cost-effective customer choices.
- Profitability: High profits correlate with strategic discounting, but fluctuations suggest a need for balanced discount policies.
- Market Analysis: Asia Pacific leads in sales, while Africa presents growth opportunities.
- Discount Impact: Discounts significantly boost sales for Chairs but have minimal effect on Labels.
# Prerequisites
- Software: Tableau Desktop (version 2023.1 or later) or Tableau Public
- Dataset: E-commerce sales dataset (ecommerce_sales.csv)
# System Requirements:
- OS: Windows 10 or later, macOS
- RAM: 8 GB or higher
- Storage: 5 GB free space
# Usage
- Open sales_dashboard.twbx in Tableau to explore the dashboard and storyboard.
- Use the geographic map to filter by region, dynamically updating all visualizations.
- Adjust the date range parameter to analyze specific periods.
- Hover over visualizations for detailed tooltips (e.g., highest sold category).
- Navigate the storyboard for a guided analysis of sales performance.
# License
This project is licensed under the MIT License. See the LICENSE file for details.
