# OLA Mobility Analytics 2023–2025

An interactive Power BI dashboard that analyzes Ola cab ride data across trips, revenue, riders and drivers.

<!-- Add a screenshot of the dashboard here: -->
<!-- ![Dashboard Preview](images/dashboard.png) -->

## Overview

This project turns raw ride data into a single-page dashboard. It shows how the business performed over time, across cities, and by service type, and lets you filter by year, month and payment mode.

## Key Metrics

| KPI | Description |
|---|---|
| Total Revenue | Sum of fares across all trips |
| Total Trips | Count of all booked trips |
| Average Fare | Revenue per trip |
| Completion Rate | Share of trips that were completed |

## Visuals

- **Monthly Revenue Trend:** line chart of Total Revenue by month
- **Revenue by Service Type:** clustered column chart
- **Revenue by City:** clustered bar chart
- **Trip Status Breakdown:** donut chart of trips by status (for example completed vs. cancelled)

## Filters (Slicers)

- Year
- Month Name
- Payment Mode

## Data Model

The report uses three tables:

| Table | Description |
|---|---|
| `Ola_Trips` | Trip-level records such as fare, city, service type, trip status and payment mode |
| `Ola_Riders` | Rider details |
| `Ola_Drivers` | Driver details |

## Tools Used

- Power BI Desktop
- DAX (measures for revenue, trips, average fare and completion rate)

## How to Use

1. Clone or download this repository.
2. Open `ola.pbix` in Power BI Desktop.
3. Use the Year, Month Name and Payment Mode slicers to explore the data.

## Repository Structure

```
├── ola.pbix        # Power BI report
├── README.md       # Project documentation
└── images/         # Dashboard screenshots (optional)
```

## Disclaimer

This project is for learning and portfolio purposes only. It is not affiliated with or endorsed by Ola. Ola logos and trademarks belong to their respective owners.
