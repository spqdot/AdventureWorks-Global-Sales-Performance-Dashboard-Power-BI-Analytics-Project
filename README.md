# AdventureWorks-Global-Sales-Performance-Dashboard-Power-BI-Analytics-Project

1. Project Overview

This project presents an interactive Sales Performance Dashboard built in Microsoft Power BI using the AdventureWorks dataset. The objective is to analyze revenue, order distribution, product performance, and geographic sales trends to generate actionable business insights.

The dashboard consolidates KPIs, category-level performance, product-level sales, and geographic distribution into a single analytical view suitable for executive and operational decision-making.

2. Business Objectives

Track actual sales vs target

Analyze sales distribution by product category

Identify top-selling products and customers

Evaluate regional and city-level sales performance

Support strategic decisions with data-driven insights

![image alt](https://github.com/spqdot/AdventureWorks-Global-Sales-Performance-Dashboard-Power-BI-Analytics-Project/blob/main/Slide1.JPG)

3. Dashboard Components
A. KPI Section

Target Sales Gauge

Displays actual sales against a predefined target

Example: $1.22M achieved vs $1.46M target

B. Category Analysis

Orders by Main Category (Bar Chart)

Bikes

Clothing

Components

Accessories
Shows order quantity distribution.

Sales by Main Category (Donut Chart)

Revenue contribution by each category

Bikes dominate revenue share (~80%+)

C. Product-Level Analysis

Top Selling Bikes (Column Chart)

Displays highest revenue-generating bike models

Includes visual benchmark/average reference line

Helps identify premium and high-demand products

D. Customer Analysis

Top Selling Companies (Pie Chart)

Revenue distribution by top customers

Highlights key B2B contributors
![image alt](https://github.com/spqdot/AdventureWorks-Global-Sales-Performance-Dashboard-Power-BI-Analytics-Project/blob/main/Slide2.JPG)

E. Geographic Analysis

World Sales by City (Map Visualization)

Revenue distribution across global cities

Bubble size and color represent sales volume

Sales by State (Map Visualization)

Concentration of sales in US states and Europe

Identifies high-performing regions

4. Key Insights

Bikes are the primary revenue driver, contributing the majority of total sales.

A small number of customers generate a significant portion of revenue (Pareto effect).

Sales are geographically concentrated in North America and parts of Europe.

Certain bike models consistently outperform others in total revenue.

Order volume does not always correlate directly with revenue (price mix effect).

5. Data Model & Transformation

Data Source: AdventureWorks dataset

Data Cleaning: Performed in Power Query

Data Modeling:

Star schema approach

Fact table: Sales

Dimension tables: Product, Customer, Geography, Date

DAX Measures:

Total Sales

Sales YTD

Target Sales

Order Quantity

Category Contribution %

Top N filtering logic

6. Tools & Technologies

Microsoft Power BI Desktop

Power Query (ETL)

DAX (Data Analysis Expressions)

Bing Maps Integration (Geospatial Analysis)

7. How to Use

Download the .pbix file from this repository.

Open it in Power BI Desktop.

Use slicers and filters to explore:

Category-wise sales

Regional performance

Product-level insights

Customer contribution

8. Project Structure
/data            -> Raw dataset (if shareable)
/dashboard       -> Power BI (.pbix) file
/images          -> Dashboard screenshots
README.md        -> Project documentation
