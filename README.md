# Coffee Shop Sales Power BI Analysis Dashboard

# Dashboard Live View:
👉 [Click here to view the Coffee Shop Sales Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTNhMzhkM2ItODUxNy00YjYzLTgxOTMtMTM5MTI0ODljZmIxIiwidCI6ImYxNjYxNTY4LTMwMjgtNDMyNC05M2E3LWFlNjI4YWE3YjcwOSJ9) 

# Abstract
This project presents an interactive Power BI dashboard for analyzing and visualizing sales data from a coffee shop chain. The dashboard provides monthly, daily, and hourly sales insights, enabling stakeholders to uncover trends, monitor KPIs, evaluate product and location performance, and make data-driven decisions for business growth.

# Problem Statement
Coffee shop leaders need to monitor sales performance efficiently, identify trends across time, locations, and products, and optimize operations. This dashboard addresses requirements such as:

Tracking monthly and daily sales, orders, and quantity sold.

Evaluating sales performance by days, hours, product categories, and individual products.

Identifying the impact of weekdays vs. weekends.

Providing detailed, interactive, and visual analytics suitable for management reporting and action-taking.

"KPI'S REQUIREMENTS: 	
1.	Total Sales Analysis:
  Calculate the total sales for each respective month.
  Determine the month-on-month increase or decrease in sales.
  Calculate the difference in sales between the selected month and the previous month.
2.	Total Orders Analysis:
  Calculate the total number of orders for each respective month.
  Determine the month-on-month increase or decrease in the number of orders.
  Calculate the difference in the number of orders between the selected month and the previous month.
3.	Total Quantity Sold Analysis:
  Calculate the total quantity sold for each respective month.
  Determine the month-on-month increase or decrease in the total quantity sold.
  Calculate the difference in the total quantity sold between the selected month and the previous month.
CHARTS REQUIREMENTS :	
1.	Calendar Heat Map:
  Implement a calendar heat map that dynamically adjusts based on the selected month from a slicer.
  Each day on the calendar will be color-coded to represent sales volume, with darker shades indicating higher sales.
  Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day.
2.	Sales Analysis by Weekdays and Weekends:
  Segment sales data into weekdays and weekends to analyze performance variations.
  Provide insights into whether sales patterns differ significantly between weekdays and weekends.
3.	Sales Analysis by Store Location:
  Visualize sales data by different store locations.
  Include month-over-month (MoM) difference metrics based on the selected month in the slicer.
  Highlight MoM sales increase or decrease for each store location to identify trends.
4.	Daily Sales Analysis with Average Line:
  Display daily sales for the selected month with a line chart.
  Incorporate an average line on the chart to represent the average daily sales.
  Highlight bars exceeding or falling below the average sales to identify exceptional sales days.
5.	Sales Analysis by Product Category:
  Analyze sales performance across different product categories.
  Provide insights into which product categories contribute the most to overall sales.
6.	Top 10 Products by Sales:
  Identify and display the top 10 products based on sales volume.
  Allow users to quickly visualize the best-performing products in terms of sales.
7.	Sales Analysis by Days and Hours:
  Utilize a heat map to visualize sales patterns by days and hours.
  Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day-hour.


# Dataset Used
👉 [Click here to view the Coffee Shop Sales Dataset](https://docs.google.com/spreadsheets/d/1GgSJcyq_I2tDwVbSqu47TWYdMzY-Opmu/edit?usp=sharing&ouid=103392594492760001145&rtpof=true&sd=true)  

The dataset records detailed transactions at several coffee shop branches, including:

Date/Time of Transaction, Store Location, Product Name & Category, Quantity Sold, Sales Value, Order ID, Product type, unit price, and Transaction quantity. 

# Approach & Methodology
Data Preparation: Cleaned and structured data for compatibility with Power BI.

Modeling & Calculations: Defined KPIs, used DAX for MoM analysis and visualization metrics.

Visualization: Built calendar heatmaps, sales breakdowns by categories, type,  locations, and time. Did daily trend analysis with the help of average daily sales over the month of period.

Interactivity: Integrated slicers, tooltips, and focus mode for detailed exploration.

Evaluation: Checked dashboard against business requirements and iteratively refined visuals.

# Results & Evaluation
April 2023 Highlights:

Total Sales: $119K (↑20.3% | +$24.1K vs last month)

Total Orders: 25,335 (↑19.3% | +4,100 vs last month)

Quantity Sold: 36,469 (↑19.9% | +6,100 vs last month)

Store-wise Sales (April 2023):

Hell's Kitchen: $40.30K (↑21.7%)

Astoria: $39.48K (↑20.2%)

Lower Manhattan: $39.16K (↑19.1%)

Top Product: Barista Espresso ($15.56K)

Peak Hours: 7AM–11AM

Category Leaders: Coffee ($45.97K), Tea ($33.36K), Bakery ($14.02K).

Similarly we can analize monthly metrics with the help of this dashboard and compare month on month chages with respect to sales, orders, and quantity sold.

# Member-wise Contributions
Waseeem Ahmad Dar: Data cleaning/processing, Power BI modeling, DAX KPIs, dashboard/MVP design, insights documentation, and all project deliverables.

# Challenges Faced
Cleaning inconsistent transaction data.

Developing dynamic, month-adjustable heatmaps.

Ensuring slicer-driven visuals update efficiently.

Segmenting and visualizing multidimensional data for actionable insights.

# Learnings
Advanced DAX for time intelligence (MoM, averages, variances).

Calendar and day/hour heatmap construction in Power BI.

Effective dashboard storytelling and interactivity principles.

# Future Scope
Add customer demographic/loyalty analytics.

Integrate cost/profit analysis for margin insights.

Enable real-time dashboard refreshes and alerts.

Expand to mobile and web dashboard sharing.

# References
Power BI Microsoft Docs

Coffee shop industry sales analytics literature

# Tech Stack
Power BI Desktop (Advanced Data Modeling, Visualization)

Advanced DAX (Business calculations, metrics)

Tooltips

CSV/Excel (Initial data handling)

Microsoft Cloud (optional, for sharing/publishing)

# Features & Highlights of the Dashboard
Dynamic Month Selector (Slicer)

KPI Cards: Sales, Orders, Quantity, Month-over-Month delta

Calendar Heatmap with day-wise sales intensity and tooltips

Sales by Weekday vs. Weekend Analysis

Location-based sales breakdowns

Top 10 Products & Product Category Analytics

Sales by Days/Hours Heatmap

Daily Sales Line Graph with Average Trendline

# Business Impact & Insights
Rapidly identify peak sales periods, best-performing products, and key store locations.

Optimize staffing, inventory, and promotions by using actionable time and product insights.

Benchmark month-on-month growth for continuous improvement.

Key Insights from the Dashboard
May 2023 saw robust double-digit MoM growth in all key metrics.

Hell’s Kitchen leads store sales, highlighting location-driven opportunity.

Top product is Barista Espresso, followed by Brewed Chai Tea and Hot Chocolate.

Weekdays drive higher sales, though order volumes are strong on weekends.

Sales spike during morning hours (7AM–11AM), matching typical coffee shop rush patterns.

# Abbrevations Used

MoM --Month on Month (means current month as compared to previous month)

LM -- Last Month

CM -- Current Month

Vs -- Verses

# Note
1. Since the dashboard analyzes month-on-month changes for sales, orders, and quantity sold, it requires data from a previous month to calculate differences and percentage changes. Therefore, for January—the first month in the dataset—the dashboard will display "infinite" (inf) change or leave the comparison fields blank, as there is no prior month to compare against
2. Because this is an individual project developed solely by Waseeem Ahmad Dar, all data modeling, analysis, and dashboard design have been completed independently.
3. Kindly Ignore Page 2 and Page 3 of the Dashboard as these pages are tooltips used for better visualization.
   
# Conclusion
This dashboard delivers a holistic, interactive analytical solution for coffee shop sales performance review, supporting business leaders with actionable, easy-to-understand insights for sustained growth.

# Author
Waseeem Ahmad Dar

Data Analytics Enthusiast | Power BI Developer | MEAL Coordinator | Consultant- Govt & Public Sector Advisory
