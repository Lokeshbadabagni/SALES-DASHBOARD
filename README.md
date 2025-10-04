Sales Performance Insights Dashboard

An interactive Power BI dashboard designed to analyze company sales performance, track profitability, and evaluate regional and sales team contributions.

---Purpose

The Sales Performance Dashboard provides a consolidated view of key business metrics such as revenue, profit, and units sold across time, regions, and sales teams. The purpose is to enable data-driven decision-making by highlighting top-performing products, regions, and sales representatives.

---Tech Stack

The dashboard was built using the following tools and technologies:
• Microsoft Excel – For raw data collection, sales transaction logging, and initial cleaning.
• Power BI Desktop – Core visualization platform for interactive dashboard creation.
• Power Query – Used for data transformation (cleaning date formats, normalizing product and region data).
• DAX (Data Analysis Expressions) – Created calculated fields such as Total Profit, Total Revenue, Revenue by Salesperson, and Cumulative Revenue Over Time.
• Data Modeling – Established relationships among tables (Products, Salespersons, Regions, Dates).
• File Format – .xlsx (raw data), .pbix (Power BI dashboard), .png (visual preview).

--- Data Source

Source: Synthetic sales dataset created in Excel to simulate real-world business transactions.
The dataset includes:
• Salesperson name, product name, region, date of sale
• Units sold and selling price per unit
• Total revenue and profit per transaction

Data was gathered from multiple Excel sheets representing monthly sales reports and merged using Power Query to create a unified data model for visualization.


--- Features / Highlights
• Business Problem

Sales leaders and managers often struggle to track performance across multiple regions and products, making it difficult to identify which areas drive growth and which need improvement.

• Goal of the Dashboard

To provide a one-stop interactive analytics tool that:

Tracks revenue and profit growth across time.

Highlights top-performing salespersons and regions.

Monitors unit sales and profitability per product.

Enables dynamic filtering by time period, region, or salesperson.

---- Walkthrough of Key Visuals

Top KPIs (Cards):

Total Revenue – Dynamic measure summarizing total sales.

Total Profit – ₹2,000 (aggregated across all transactions).

Total Units Sold – 75 units.

Pie Chart (Revenue by Salesperson):
Displays each salesperson’s contribution to total revenue, helping identify top performers and underperforming sales reps.

Stacked Area Chart (Revenue by Time):
Illustrates total revenue trends across year, month, and day, enabling seasonality and trend analysis.

Clustered Bar Chart (Revenue by Region):
Compares total revenue across North, South, East, and West regions to identify geographic strengths.

Data Table (Product-Level Revenue):
Tabular breakdown of products with respective total revenue and profit, supporting detailed performance review at product level.

--- Business Impact & Insights

Strategic Targeting: Identified regions contributing the most revenue to guide marketing and logistics planning.

Performance Recognition: Helped leadership identify top-performing salespersons for reward and retention strategies.

Inventory Planning: Product-level analysis supports better forecasting and stock management.

Revenue Optimization: Revealed underperforming categories and regions needing price or promotional adjustments.
