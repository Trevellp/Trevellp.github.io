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

## Sample Code
```python
sub_counts = (
    dff.groupby("substance")["record_id"]
    .count()
    .reset_index(name="count")
)
