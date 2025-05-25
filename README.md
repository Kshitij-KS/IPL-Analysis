# IPL-Analysis

## Problem Statement

This dashboard provides a comprehensive analysis of Indian Premier League (IPL) matches and performance statistics. It is designed to help teams, analysts, and fans understand the dynamics of the league better, identify top-performing players, assess team strengths and weaknesses, and gain insights through data visualizations.

By using this dashboard, stakeholders can:

- Evaluate player performance across seasons

- Compare teams based on win percentages, toss decisions, and venues

- Identify patterns in match outcomes based on various conditions

- Understand the impact of toss, venue, and match location on performance

### Steps followed 

- Step 1: Loaded the IPL dataset (CSV format) into Power BI Desktop.

- Step 2: Opened Power Query Editor and enabled "column distribution", "column quality", and "column profile" for thorough data profiling.

- Step 3: Performed necessary data cleaning, such as handling null values and filtering irrelevant columns.

- Step 4: Created calculated columns for:

  - Year extraction from match dates

  - Win margin type (by runs/wickets)

- Step 5: Created DAX measures for:

  - Total matches played

  - Total wins per team

  - Win percentage

  - Most frequent venues

  - Toss win vs match win correlation

- Step 6: Added slicers for filtering data based on:

  - Season/Year

  - Team

  - Venue

  - Toss decision

- Step 7: Designed visuals such as:

  - Bar charts for top players and teams

  - Line graphs for performance trends over seasons

  - Donut charts for match result types

  - Tables for match summaries and top stats

- Step 8: Included KPIs using card visuals to show key metrics like total matches, total teams, and average win margins.

- Step 9: Applied themes for visual consistency and improved aesthetics.

- Step 10: Published the report to Power BI Service for sharing and interactive usage.

 ### Filters & Interactivity

- Year-wise filter to analyze specific seasons

- Team selector to focus on particular teams

- Venue-based insights with heatmap visuals

- Toss decision filters for comparative analysis

### Snapshot of the Dashboard

![Image](https://github.com/user-attachments/assets/fe292a50-9081-4a5f-ba51-7c9cafc379db)
