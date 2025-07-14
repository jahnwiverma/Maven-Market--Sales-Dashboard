# Maven-Market--Sales-Dashboard

A dynamic, interactive data visualization tool built to explore sales of product of Maven Market - Focusing on analyzing weekly sales performance, brand-wise profitability, and regional trends to provide actionable insights

PURPOSE:

To equip sales and business teams with a quick, interactive way to monitor key performance indicators, spot underperforming brands or regions, and track progress toward monthly targets — all in one centralized dashboard.

TECH STACK:

This dashboard was built using the following tools and technologies Tools Used:

📊 Power BI Desktop – Used for creating interactive reports and dashboards with drag-and-drop visuals.

🔄 Power Query – Utilized for cleaning, transforming, and loading data from multiple sources.

🧮 DAX (Data Analysis Expressions)– Applied to build calculated columns and measures for custom insights and KPIs.

🧩 Data Modeling – Established relationships between tables (Customer, Product, Store, Regions, Calendar, Transactions data & return data) to enable accurate, cross-filtered analysis.

📁 .pbix File Format – The native file format for saving and sharing Power BI reports.

DATA SOURCE:

Dataset provided as part of the bonus project in the Udemy course "Microsoft Power BI Desktop for Business Intelligence" by Maven Analytics. Used solely for educational and portfolio purposes.

HIGHLIGHTS:

📌Business Problem -The sales team lacks a centralized and visual way to track weekly revenue trends, brand-level performance, and regional insights. Without quick access to key sales metrics, it becomes difficult to monitor progress toward targets, identify underperforming areas, and make timely, data-driven decisions.

🎯Business Goal -To create an interactive dashboard that enables sales and business teams to monitor weekly sales, track monthly KPIs, and analyze profitability across brands and regions — all in one place — to support faster and more informed decision-making.

📊KEY VISUALS USED:

1. Matrix (Product Brand Analysis)

-Shows Total Transactions, Profit, Profit Margin, and Return Rate by product brand.

-Used to compare brand-level performance with conditional formatting for quick insights on best and worst-performing brands.

2. KPI Cards (Monthly Overview)

-Displays Current Month Transactions, Profit, and Returns vs. last month.

-Used to track performance trends and compare key sales metrics month-over-month, with color coding to highlight good or poor results.

3. Map (Transactions by Store City)

-Shows geographical spread of transactions across cities.

-Used to identify high-performing store locations and support regional performance analysis.

4. Country Slicer (Store Country Filter)

-Allows filtering visuals by store country with a “Select All” option.

-Used to enable region-specific analysis and improve dashboard interactivity.

5. Treemap ( Store-wise Transactions (Drill-down))

-Breaks down Total Transactions by country, state, and city.

-Used for multi-level geographic analysis with drill-up and drill-down capabilities.

6. Column Chart (Weekly Revenue Trending)

-Displays total revenue by week for the year 1998.

-Used to track weekly performance trends and spot revenue patterns.

7. Gauge Chart (Revenue vs. Target)

-Compares total revenue against a predefined target.

-Used to evaluate progress toward monthly goals in a simple, visual format.

8. Bookmarks with Buttons – Interactive Navigation

-Custom bookmarks created for Portland (1000 sales), Vancouver (monthly returns), and Zacatecas (monthly profit), each with a button and icon.

-Used to highlight key insights and enable quick navigation to important views.

📈 BUSINESS IMPACT & INSIGHTS:

-Enabled quick, visual analysis of sales performance across time, brands, and regions — improving decision-making, target tracking, and identification of underperforming areas.

-Identified weekly revenue patterns and seasonal trends.

-Ranked top 30 brands by transactions and profit margin.

-Highlighted cities like Portland and Vancouver for notable sales/returns.

-Tracked KPIs against targets to monitor monthly progress.

-Used bookmarks to spotlight key business milestones instantly.

⚠️ *Known Issues & Setup Notes*

*If you're using a non-US regional setting (like English - India), you may encounter errors with date fields in Power BI due to formatting conflicts.

*Fix: Set your Power BI regional settings to English (United States) to ensure the dashboard loads and displays date values correctly.


