# urban-bike-sharing-analysis using Power BI
Urban Bike Sharing Performance Dashboard (2022–2025) Using Power BI

## Project Overview

This project analyzes an urban bike-sharing system using Power BI to understand performance, utilization, and growth trends from 2022 to 2025. The analysis focuses on identifying demand patterns, underperforming cities, and operational efficiency improvements.

---

##  Objectives

* Analyze bike availability trends across years
* Identify top and low-performing cities
* Evaluate station utilization efficiency
* Detect stations with zero bike availability
* Analyze unused capacity across stations
* Compare banking vs non-banking performance
* Evaluate bonus vs non-bonus usage

---

##  Dataset Description

The dataset contains station-level operational data, including:

* Station Name
* City Name
* Available Bikes
* Available Bike Stands
* Bike Stands (Total Capacity)
* Status (OPEN / CLOSED)
* Banking (Payment Facility)
* Bonus (Incentives)
* Latitude & Longitude
* Last Update (Date & Time)

---

## Data Preparation

* Removed null and inconsistent values
* Standardized column names
* Applied Trim and Clean functions
* Combined date and time columns
* Ensured correct data types for all fields

---

##  Data Model

A star schema approach was used:

**Fact Table**

* Bike_Data

**Dimension Tables**

* Dim_City
* Dim_Station
* Dim_Year

**Relationships**

* City → One-to-Many
* Station → One-to-Many
* Year → One-to-Many

---

##  Key Analysis & Insights

### 🔹 City Performance

* Cities like **Bruxelles-Capitale** and **Lyon** show highest utilization
* Cities like **Rouen** and **Vilnius** show very low performance

### 🔹 Year-wise Trend

* 2022–2023: Very low activity
* 2024: Initial growth phase
* 2025: Massive expansion with 19,450 bikes

### 🔹 Capacity Utilization

* High empty capacity in cities like **Cergy-Pontoise** and **Mulhouse**
* Balanced usage in cities like **Lyon** and **Toulouse**

### 🔹 Banking vs Non-Banking

* Minimal difference in performance
* Slight advantage for banking stations in 2025

### 🔹 Bonus vs Non-Bonus

* Bonus usage slightly higher (~51%)
* Indicates small positive impact of incentives

### 🔹 Geographic Distribution

* High concentration in **Western Europe**
* Low presence in smaller and eastern cities

---

##  Dashboard Features

* Year-wise trend analysis (2022–2025)
* City-wise performance comparison
* Banking vs Non-Banking analysis
* Bonus vs Non-Bonus usage
* Map visualization (Latitude & Longitude)
* Capacity utilization analysis

---

##  Final Insights

* The system evolved from a low-usage phase (2022–2023) to a high-growth phase (2025)
* Growth is uneven, with a few cities dominating performance
* Infrastructure expansion and incentives improved overall efficiency
* Underperforming cities still require optimization

---

##  Analytical Approach

* Descriptive: Understanding overall trends and performance
* Diagnostic: Identifying reasons for low/high performance
* Predictive: Forecasting future growth trends
* Prescriptive: Suggesting improvements for optimization

---

##  Conclusion

The bike-sharing system has transformed significantly, with major growth in 2025 driven by infrastructure expansion and improved user engagement. While some cities dominate performance, others require better planning and resource allocation to achieve balanced system efficiency.

---

##  Tools Used

* Power BI
* DAX (Data Analysis Expressions)
* Power Query

---

##  Project Files

* Bike_Stations_Sharing_Analysis (.pbix)
* Project Report (.pdf)
* Bike_Stations_Sharing_Data (.xlsx)
* Bike_Stations_Sharing_Dashboard (.pdf)

---

##  Author

Ezhilarasi S
Aspiring Data Analyst | Excel | Power BI | SQL

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
