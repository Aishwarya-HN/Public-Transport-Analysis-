
# Public Transport Analysis Dashboard in Excel

This project presents a comprehensive dashboard built in Excel to analyze public transport data, focusing on revenue, passenger counts, and safety metrics across different routes and transport types.

## Problem Overview
Efficient management of public transportation requires clear insights into revenue generation, passenger usage, and accident occurrences. This dashboard addresses the following key challenges:

-Understanding revenue trends over time and by vehicle type.
-Identifying routes with high passenger traffic for better resource allocation.
-Evaluating safety by tracking accident counts by transport mode.
-Enabling interactive filtering to explore data dynamically by date, route, and transport type.

## Features
-Revenue By Months and Vehicle: Bar chart comparing monthly revenue for buses, metro, and trams.
-Average Passenger Count: Bar chart showing passenger load across different routes.
-Revenue Distribution: Horizontal bar chart illustrating revenue contribution by each route.
-Accident Reports: Pie chart showing accident counts segmented by transport mode.

## Filters: Interactive slicers for selecting specific months, transport types, and routes.

## Dataset
The data includes monthly revenue, passenger counts, route details, and accident reports for buses, metro, and trams operating in various city routes.

## Usage
Open the Excel file and use the slicers on the left to filter data by date, transport type, or route. The charts will update automatically to reflect your selections.

# Public Transport Analysis Dashboard in Power BI

This Power BI dashboard provides an interactive analysis of public transport data focused on Bus, Metro, and Tram services. The goal is to offer insights into passenger behavior, revenue generation, route efficiency, and service utilization to support data-driven decision making for urban transport management.

 ## Features

- Transport Type Selection: Filter analysis by Bus, Metro, or Tram.
- Key Metrics: View average revenue per passenger, average travel distance, and occupancy rates.
- Monthly Distance Trends:Track average distance covered by passengers over time.
- Top Revenue Routes:Identify the most profitable transport routes.
- Passenger Distribution: Visualize passenger counts by transport type.
- Fine Collection and Route Activity:Analyze fines collected alongside route activity levels.
- Trip Duration Overview: Measure trip durations to assess service performance.
- 
## DAX Measures
- Avg Revenue per Passenger = 
 ![image_alt](https://github.com/Aishwarya-HN/Public-Transport-Analysis-/blob/1a566cf34d7be41c89e6301db2724990e8a22f80/Screenshot%202025-08-11%20103728.png)
- Top 5 Maintaince = 
 ![image_alt](https://github.com/Aishwarya-HN/Public-Transport-Analysis-/blob/f2a79b0c77aefd5b0ebfea32a986b9e9c9b1914f/Screenshot%202025-08-11%20103753.png)
- Top 5 Routes Revenue = 
![image_alt]( https://github.com/Aishwarya-HN/Public-Transport-Analysis-/blob/f2a79b0c77aefd5b0ebfea32a986b9e9c9b1914f/Screenshot%202025-08-11%20103804.png)
- Total Passengers =
 ![image_alt](https://github.com/Aishwarya-HN/Public-Transport-Analysis-/blob/f2a79b0c77aefd5b0ebfea32a986b9e9c9b1914f/Screenshot%202025-08-11%20103829.png)
- Total Revenue =
 ![image_alt](https://github.com/Aishwarya-HN/Public-Transport-Analysis-/blob/f2a79b0c77aefd5b0ebfea32a986b9e9c9b1914f/Screenshot%202025-08-11%20103838.png)
- YoY Revenue % = 
![image_alt]( https://github.com/Aishwarya-HN/Public-Transport-Analysis-/blob/f2a79b0c77aefd5b0ebfea32a986b9e9c9b1914f/Screenshot%202025-08-11%20103856.png)

## Data Source

The dataset includes public transport trip records, passenger counts, revenue, fines, and trip durations for various routes and transport types across different months in 2025.

## How to Use

1. Use the Transport Type buttons to filter the dashboard.
2. Explore key metrics for a quick summary of transport performance.
3. Drill down into route-level data and fines analysis.
4. Use the pie charts and bar charts to compare transport types and routes.
5. Analyze trip durations to identify bottlenecks or delays.

## Tools and Technologies

- Power BI for data visualization and dashboard creation.
- Data cleaning and preparation performed prior to visualization.

## Goals

- Improve operational efficiency by identifying high and low-performing routes.
- Optimize resource allocation based on occupancy and revenue data.
- Enhance passenger experience by monitoring trip durations and occupancy.
- Support enforcement efforts by highlighting areas with higher fine collections.

---

# python
This Python script loads a CSV dataset, performs basic exploratory checks, and applies common cleaning steps to prepare the data for analysis or modeling.

## What it does
Loads the dataset from a specified CSV file.
Shows basic info: shape, columns, missing values count, and a preview of the first few rows.
Cleans the data by:
Stripping whitespace from all string (object) columns.
Filling missing numerical values with the median of each column.
Filling missing categorical values with the mode (most frequent value).
Removing duplicate rows.
Converting data types such as date columns.
Outputs the cleaned dataset as a new CSV file.

## How to use
Update the file_path variable in the script with your dataset’s file location.
Run the script in a Python environment with pandas installed.
After cleaning, find the new CSV file saved at the path specified by cleaned_path.




