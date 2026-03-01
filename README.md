📊 House Price Analysis – Power BI Codveda Internship | Level 2
📌 Project Overview

This project was completed as part of the Codveda Power BI Internship – Level 2.

The main objective was to apply intermediate Power BI concepts including:

Star Schema Data Modeling

Creating Relationships

Writing DAX Measures

Building Advanced Interactive Dashboards

Applying Professional Formatting

This project analyzes house pricing data to uncover pricing patterns across cities, bedroom configurations, and property features.

-------------------------------------------------------------------------------------------------------------------------------------------------------

📂 Dataset

House_Prediction_Dataset.csv

A structured housing dataset containing:

Property details

Area (SqFt)

Bedrooms & Bathrooms

Furnishing Status

Air Conditioning

City

Price

-------------------------------------------------------------------------------------------------------------------------------------------------------

🏗 Data Modeling

To follow best practices, a Star Schema model was created:

Fact_House → Main transactional table

Dim_City → Dimension table (Unique Cities)

A One-to-Many relationship was established between:

Dim_City (1) → Fact_House (*)

This improves performance and follows professional BI modeling standards.

-------------------------------------------------------------------------------------------------------------------------------------------------------

🧮 DAX Measures Created

The following measures were created using DAX:

Total Sales = SUM(Price)

Average Price = AVERAGE(Price)

Total Properties = COUNT(PropertyID)

Average Area = AVERAGE(Area_SqFt)

Houses With AC = CALCULATE with filter condition

These measures demonstrate understanding of:

SUM

AVERAGE

COUNT

CALCULATE

Filter Context

-------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Dashboard Components

The final interactive dashboard includes:

📌 KPI Section

Total Sales

Average Price

Total Properties

Average Area

Houses With AC

-------------------------------------------------------------------------------------------------------------------------------------------------------

📈 Visual Analysis

Total Sales by City (Column Chart)

Average Price by Bedrooms (Column Chart)

-------------------------------------------------------------------------------------------------------------------------------------------------------

🎛 Interactive Filters

City Slicer

Furnishing Status Slicer

Air Conditioning Slicer

-------------------------------------------------------------------------------------------------------------------------------------------------------

📋 Detailed Table

City-wise summary

Total Sales

Total Properties

Area and Property breakdown

-------------------------------------------------------------------------------------------------------------------------------------------------------

🔎 Key Insights

Hyderabad generated the highest total sales.

4-bedroom properties show the highest average price.

Air-conditioned houses represent a significant share of properties.

City and furnishing type significantly influence pricing.

-------------------------------------------------------------------------------------------------------------------------------------------------------

🧰 Tools Used

Power BI Desktop

Power Query

DAX

Star Schema Modeling

-------------------------------------------------------------------------------------------------------------------------------------------------------

✅ Project Status

✔ Level 2 Completed Successfully 🚀
✔ Professional Data Modeling Implemented
✔ Advanced DAX Measures Created
✔ Interactive Dashboard Designed

Ready for Level 3 🔥
