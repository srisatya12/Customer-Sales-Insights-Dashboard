# Sales Performance Dashboard

## Overview

This project involves building an interactive dashboard to track sales performance using data from a new CRM system. The dashboard helps sales managers monitor their team's quarterly performance, visualize won and lost opportunities, and break down sales data by agents, quarters, and regional offices.

The dashboard is powered by pivot tables and charts to provide clear insights into key sales metrics like opportunities won, percentage of deals closed, and sales agent performance. It integrates data from multiple CSV files, including sales pipelines, sales teams, and managers, and is designed to offer easy filtering and interaction for sales managers.

## Objectives
1. **Data Profiling**: Explore the data from the CSV files (`sales_pipeline.csv`, `sales_teams.csv`) and identify missing values, won opportunities, and products sold over time.
2. **Pivot Table Analysis**:
   - Created a pivot table to show opportunities won by quarter.
   - Added a breakdown of won vs. lost opportunities by quarter.
   - Generated a pivot table showing opportunities won per sales agent, sorted in descending order.
3. **Dynamic Visualization**:
   - Pivot tables were restructured to place quarters as columns and sorted to show the most recent quarter first.
   - A scorecard chart visualized opportunities won in the most recent quarter (Q2 2017) compared to the previous quarter.
   - A pie chart visualized the percentage of deals won and lost in the most recent quarter.
   - A bar chart visualized opportunities won by sales agents for the most recent quarter.
4. **Interactive Filters**: Added slicers for regional offices and managers to allow for dynamic filtering of the data.

## Features
- **Opportunities Won by Quarter**: Pivot table showing the total number of won opportunities, allowing managers to track performance across quarters.
- **Won vs. Lost Opportunities**: Pivot table and pie chart breakdown of the percentage of won and lost opportunities in each quarter.
- **Sales Agent Performance**: Bar chart visualizing which agents closed the most deals in the most recent quarter.
- **Interactive Slicers**: Filters for regional offices and managers to easily view data relevant to specific teams or regions.
- **Scorecard Comparison**: A scorecard chart comparing the most recent quarter's performance with the previous one to highlight trends.

## Tools and Technologies
- **Data Source**: CSV files (`sales_pipeline.csv`, `sales_teams.csv`, `manager.csv`)
- **Visualization**: Google Sheets (pivot tables, scorecards, pie charts, bar charts)
- **Languages**: Data analysis and visualization in Google Sheets

## Insights
- The dashboard provides a comprehensive view of sales team performance over time.
- It enables sales managers to identify top-performing agents and visualize trends in won vs. lost opportunities.
- The comparison of quarterly performance helps in tracking growth or declines in sales metrics.

## Live Document
Explore the live spreadsheet [here](https://docs.google.com/spreadsheets/d/1052btDhlZKeWviDys7DLd_q8X0FLDzNC_sRzWDkkglY/edit?usp=sharing).
