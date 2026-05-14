
# Sales Overview Analysis Dashboard

A dynamic Power BI dashboard designed to track and analyze key performance indicators (KPIs) across four major US regions. This project provides a comprehensive view of business health by allowing users to toggle between Sales, Profit and Quantity metrics with year over year comparisons.

##  Project Overview

The goal of this project is to provide stakeholders with an interactive tool to visualize performance trends and geographic distribution. The dashboard facilitates data driven decision making by highlighting regional strengths and identifying areas for growth.

### Key Features

**Dynamic Metric Selection:** Users can switch the entire dashboard view between **Sales, Profit and Quantity** using a custom slicer.


**Time-Intelligence:** Integrated year filters (2021–2024) with automatic **Previous Year (PY)** and **Year over Year (YoY)** calculations.


**Regional Breakdowns:** Dedicated sections for **Central, East, South and West** regions each featuring monthly sparklines and average trend lines.


**Geospatial Analysis:** A bubble map visualizing sales distribution across states, where bubble size corresponds to volume.


**Comparative Insights:** A detailed metrics table showing CY, PY and YoY performance across all three core KPIs.

---

## ️ Project Workflow

The development followed a structured data analytics lifecycle:

1.**Requirement Gathering:** Defined business needs and KPI definitions.


2.**Data Connection & Cleaning:** Connected to data sources and performed quality checks/transformations.


3.**Data Modeling:** Established relationships between tables for accurate filtering.


4.**DAX Calculations:** Developed measures for Time Intelligence (PY, YoY) and dynamic metric switching.


5.**Dashboard Layout & Design:** Created a professional UI/UX background and layout for better readability.


6.**Insights Generation:** Finalized charts to highlight actionable business trends.



---

## Dashboard Visuals


### Visual Components:

***Monthly Sparklines:** Bar charts showing monthly trends for the selected metric with an average reference line.


***Sales by State (Bar Chart):** Provides a ranked breakdown of performance by state for easy comparison.


***Metrics Grid:** A comprehensive table displaying:
* Current Year (CY) vs. Previous Year (PY).

* YoY Growth




---

##  Technical Details

* **Tool:** Power BI Desktop
* **DAX Functions Used:** `CALCULATE`, `SAMEPERIODLASTYEAR`, `SWITCH` (for dynamic measures) and `DIVIDE`.
* **Data Source:** Sales and Regional Performance Dataset.

---
