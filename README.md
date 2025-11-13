# Aramark-MLB-sales-analytics
End-to-end Power BI, Python, and SQL project analyzing MLB ballpark concessions for Aramark — forecasting revenue, modeling cost types, and uncovering venue-level sales insights.


**#Project Overview**
This project analyzes MLB ballpark concessions data for Aramark, covering 2023–2024 seasons and over 9.7 million transactions.
The goal was to build a centralized sales intelligence dashboard that helps Aramark understand:
Which venues generate the most revenue
What products (Level 2 categories) drive volume vs. profit
How weekend/weekday, time of day, and seasonality influence sales
What stand types (GC, Portable, Hawkers, etc.) perform best
How pricing and cost types affect customer behavior
The result is a fully interactive Power BI dashboard with drilldowns from Org → Venue → Stand Group → Level 2 Category, backed by a clean semantic model and DAX measures.

**#Objectives**
Build a Power BI semantic model capable of handling 9.7M+ rows for fast slicer-level analysis
Provide Aramark leadership with venue-level revenue insight and operational patterns
Identify top-selling categories, pricing trends, and volume drivers
Compare performance across weekdays vs. weekends, day vs. night, seasonal shifts, and engagement segments
Support future decisions around product mix, staffing, inventory, and stand placements

**#Tools & Technologies**
Power BI (data modeling, DAX, calculated tables, RLS-ready structure)
SQL (joins, cleaning, transformations)
Python (pandas, NumPy, clustering, forecasting models)
Power Query (ETL, parameterized refresh)
Excel (initial data profiling)

**#Data Modeling & Engineering**
leaned & merged raw POS, venue, and game-level datasets
Built a fact table (sales + units) and dimensions (venue, stand group, category level, date, cost type, engagement)
Implemented relationships and hierarchies for deep drilldowns
Created DAX measures for:
Total Sales
Total Units
Average Price per Item
Engagement Ratios
Season-level KPIs
Weekend vs. Weekday Performance
Designed slicers for season, time of day, venue, category levels, event month, etc.

**#Dashboard Features**
1. Summary View
2. Sales Drivers View
3. Level-2 Category Analysis


**#Key Insights**
General Concessions & Portable stands drive the majority of total sales.
Premium Packages, Domestic Packages, and Liquor dominate high-margin categories.
Weekends outperform weekdays across all KPIs (sales, units, attendance).
Night events generate significantly more revenue than daytime events.
Seasonal shifts show peak performance in June–August with declining sales post-September.

**#Impact**
This dashboard helps Aramark:
Identify high-performing venues and stands for staffing and inventory planning
Understand pricing vs. volume behavior across 44+ Level-2 categories
Make venue-specific product mix decisions
Forecast demand using seasonality and historical patterns
Optimize operations and improve customer experience across MLB ballparks
