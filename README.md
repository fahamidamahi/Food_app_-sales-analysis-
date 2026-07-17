# Food_app_-sales-analysis ((Interactive Dashboard creation using MS Excel)
## Project Objective
An interactive Sales Dashboard built in Microsoft Excel using Power Query, Data Modeling, and DAX to analyze food delivery sales performance, customer ratings, and regional demand across India. The dashboard integrates multiple datasets, applies ETL processes, and delivers dynamic business insights through slicer-driven interactivity.
## Dataset
- <a href="https://github.com/fahamidamahi/Food_app_-sales-analysis-/tree/master/Raw%20Dataset">Dataset</a>
## Problem Statement
- KPIs at the top: Total Sales, Average Rating, Average Order Value, Ratings Count, and Total Orders.
- Comparison visuals: Monthly sales trend (Jan–Aug), daily sales trend (Sun–Sat), and weekly sales trend across 36 weeks.
- Category insights: Revenue split by food type (Veg vs. Non-Veg).
- Regional insights: State-wise sales performance visualized on a map of India, and quarter-wise (Q1–Q3) breakdown of sales, rating, and total orders by state.
- City insights: Top-5 cities by sales, led by Bengaluru.
- Interactivity: Ability to filter by month, food category (Desi, Chinese, Pasta, Roll, Sides, and more), and restaurant name.

- Dashboard Interaction <a href="https://github.com/fahamidamahi/Food_app_-sales-analysis-/blob/master/Final%20Dashboard.png">View Dashboard</a>
## Process 
1️⃣ Data Import & Transformation (Power Query)
- Imported raw sales, restaurant, and order datasets into Power Query
- Cleaned and structured data
- Handled inconsistencies and formatting issues
- Created new columns from existing columns
- Transformed date fields for time-based analysis (monthly, daily, weekly trends)

2️⃣ Data Modeling
- Established relationships between:
  Orders ↔ Restaurant (via Restaurant ID)
  Orders ↔ Location (via State/City)
- Built a structured data model inside Microsoft Excel


3️⃣ Analysis Layer
- Created DAX measures for KPI calculations
- Applied calculated metrics and aggregations
- Designed KPI summary cards (Total Sales, Average Rating, Average Order Value, Ratings Count, Total Orders)

4️⃣ Visualization & Dashboard
- Built interactive line, bar, and donut charts
- Designed a state-wise sales heat map using the Bing Maps visual
- Designed dynamic dashboard layout
- Implemented Slicers for filtering: Month, Category, Restaurant Name
- Developed a fully interactive reporting interface

## Dashboard

<img width="1803" height="841" alt="Final Food_app_-sales-analysis Dashboard" src="https://github.com/fahamidamahi/Food_app_-sales-analysis-/blob/master/Final%20Dashboard.png" />

## Business Insights Derived
- Sales show a dip in February–March, followed by steady recovery through August.
- Non-Veg orders contribute the majority of revenue (64%) compared to Veg (36%).
- Bengaluru is the top-performing city by sales (₹5.46M), followed by Lucknow, Hyderabad, Mumbai, and New Delhi.
- Q2 recorded the highest sales and order volume among the three quarters, while Q3 saw a decline.
- Weekend sales (Friday–Saturday) trend higher than early-weekday sales, peaking on Saturday.
- Average customer rating remains consistently strong at 4.34, reflecting stable service quality across regions.

## Conclusion 
The dashboard delivers a clear view of food delivery sales performance, highlighting seasonal trends, food type preferences, and regional demand patterns. It enables quick identification of top-performing cities, quarters, and food categories, supporting effective data-driven decision-making for the business.
