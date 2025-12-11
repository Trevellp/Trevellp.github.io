---
layout: project
type: project
image: img/DashboardLogo.png
title: "DOH Substance Use Dashboard"
date: 2025
published: true
labels:
  - Python
  - Dash
  - Plotly
  - Data Visualization
summary: "A Python Dash dashboard that recreates and improves a Hawaiʻi DOH substance use emergency discharge dashboard (2018–2024), with interactive filters, KPIs, and tables."
---



# Hawaiʻi DOH Substance Use Dashboard (2018–2024)

## Overview
This project recreates and improves a Department of Health Power BI dashboard using
Python, Dash, Plotly, and custom CSS. The goal was to build a completely interactive,
mobile-friendly web app that matches government design standards while supporting
advanced filtering, tables, and bar charts.

The dashboard uses two CSV datasets containing over 128,000 discharge records.
I engineered a backend workflow that loads, merges, cleans, and aggregates the data
on demand with responsive UI updates.

## Key Features
- Fully interactive web dashboard built with **Dash & Plotly**
- Custom **Bootstrap-based theme** for DOH-style UI consistency
- Horizontal bar chart for substance types
- Interactive filters: age group, sex, county, year, resident status
- KPI cards and dynamic tables replacing Power BI visuals
- Optimized callback structure for fast filtering on 128k rows
- Mobile-responsive layout with custom CSS utilities

## Tech Stack
- Python, Dash, Plotly, Pandas  
- Bootstrap / custom CSS  
- SQLite caching layer (for performant repeated queries)



## Dashboard Screenshots

<p align="center">
  <img src="/img/Dashboard1.png" width="850" style="border-radius: 10px;">
  <br>
  <em>Figure 1: Main dashboard overview including KPIs and filtering options.</em>
</p>

<p align="center">
  <img src="/img/Dashboard2.png" width="850" style="border-radius: 10px;">
  <br>
  <em>Figure 2: Additional dashboard views visualizing polysubstance and demographic distributions.</em>
</p>
This dashboard visualizes Hawaiʻi Department of Health substance use emergency
discharge data from 2018 to 2024. It recreates and extends an original Power BI
dashboard using Python, Dash, Plotly, and custom CSS.

## Sample Code
```python
sub_counts = (
    dff.groupby("substance")["record_id"]
    .count()
    .reset_index(name="count")
)
