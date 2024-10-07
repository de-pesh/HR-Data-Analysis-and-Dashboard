# HR Insights Dashboard - Power BI Project

This repository contains a Power BI dashboard project designed to provide insights into HR-related metrics such as employee attendance, work from home (WFH) percentages, and sick leave (SL) percentages. The dashboard helps HR teams monitor and analyze employee trends over time, enabling data-driven decision-making.

## Overview

The **HR Insights Dashboard** focuses on three key metrics:

- **Attendance %**: The percentage of employees who were present during the selected period.
- **WFH %**: The percentage of employees working from home.
- **SL %**: The percentage of employees who took sick leave.

The dashboard offers visual representations of these metrics over time, making it easier to track fluctuations, analyze trends, and identify areas for improvement.

![Dashboard Overview](./dashboard.png)

## Features

1. **Attendance, WFH, and SL metrics**: Displays overall attendance, WFH, and SL percentages for the selected date range.
2. **Trend Analysis**:
   - Attendance, WFH, and SL trends over time, represented by line graphs.
   - Breakdown of metrics by day of the week for more granular insights.
3. **Employee Breakdown**:
   - List of employee-specific data, including attendance percentage, present days, and WFH percentage.
4. **Date Range Selection**: Allows users to filter the dashboard by custom date ranges.
5. **Sick Leave and WFH Trends**: Visualizations show peaks and dips in WFH and SL across different time periods.
6. **Detailed Daily Data**:
   - Displays specific employee data for selected days.
   - Employee status (e.g., WFH, HML, HPL) for each day is available for detailed tracking.

## How to Use

### Prerequisites

- **Power BI Desktop**: Ensure you have Power BI Desktop installed on your machine. You can download it from [here](https://powerbi.microsoft.com/desktop).

### Running the Dashboard

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/de-pesh/HR-Data-Analysis-and-Dashboard.git
   ```

2.	Open the Power BI .pbix file in Power BI Desktop.
3.	Load your dataset (if not already included) and refresh the report to ensure all data is up to date.
4.	Use the Date Range filter at the top right to select the period you’d like to analyze.
5.	Review the key metrics, trends, and employee data to get insights into HR performance.

### Key Visuals

-	Attendance % Over Time: A green line chart showing attendance trends, highlighting significant dips or increases in employee presence.
-	Sick Leave % Over Time: A red line chart visualizing sick leave patterns, with spikes indicating periods where sick leave was higher than average.
-	Work From Home % Over Time: A blue line chart showing trends in WFH percentages, helping you track remote work patterns.
-	Day of Week Analysis: Breakdown of attendance, WFH, and SL percentages by each day of the week for a detailed understanding of weekly trends.

### Customization

You can customize the dashboard according to your organization’s needs:

-	Add new metrics or dimensions.
-	Modify the date filters to provide more flexible date ranges.
-	Update the employee list and ensure data refresh functionality is active for live data updates.

### Future Improvements

-	Add more advanced filters like department, role, or location for deeper insights.
-	Include additional KPIs such as overtime, vacation, or leave balances.
-	Implement predictive analytics to forecast future attendance trends based on historical data.
