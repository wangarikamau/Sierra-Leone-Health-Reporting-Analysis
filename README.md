## Sierra Leone Health Facility Reporting & Data Quality Dashboard ((DHIS2-Based))

# Project Summary

This project analyzes health facility reporting performance in Sierra Leone using data exported from DHIS2.

The dashboard evaluates two critical data quality indicators:

Reporting Completeness
Reporting Timeliness

It is designed to support Monitoring & Evaluation (M&E) teams, NGOs, and health ministries in identifying reporting gaps, improving data reliability, and strengthening decision-making.

# Real-World Context (DHIS2)

In many countries, DHIS2 is the backbone of national health reporting systems. Facilities submit monthly reports that are used for:

Disease surveillance
Resource allocation
Program evaluation

However, raw DHIS2 exports are often:

Wide-format and difficult to analyze
Inconsistent across districts
Lacking immediate insight into reporting failures

This project demonstrates how to transform DHIS2 data into actionable intelligence.

# Technical Workflow
1. Data Extraction (DHIS2)
Exported aggregated reporting data from DHIS2
Focused on facility-level reporting indicators across districts
2. Data Transformation (Power Query)
Converted wide DHIS2 format → long format using unpivoting
Cleaned and standardized date and district fields
Prepared dataset for time-series analysis
3. Data Modeling & DAX (Power BI)

Created key measures:

Completeness Rate (%)
Timeliness Rate (%)
Reporting Gap = Completeness − Timeliness
National averages for KPI cards
4. Dashboard Design
Applied F-pattern layout for readability
Used:
Dual-line trend chart (Completeness vs Timeliness)
Ranked district bar chart
Drill-down matrix for monthly performance
Conditional formatting based on 80% national target
# Key Insights
# National Trend
Reporting peaked at 97% in August 2025
Followed by a ~40% decline in Q4, indicating possible:
System outages
Staffing or training gaps
# District Performance
Kono and Bonthe consistently fall below 70%
High-performing districts (e.g., Moyamba, Kenema) maintain >90%
# Operational Behavior
Strong alignment between completeness and timeliness suggests:
→ Batch data entry instead of real-time reporting
# Programmatic Impact

This dashboard enables:

Targeted interventions (e.g., training, supervision)
Early detection of reporting failures
Improved reliability of DHIS2 data for decision-making
# Dashboard Features (Based on Current Design)
Interactive Filters (Left Panel):
Date range slicer
Organization/district filter
KPI Cards (Top):
Avg Completeness (~81.8%)
Avg Timeliness (~81.8%)
Reporting Gap (~18.2%)
Trend Analysis:
Solid line → Reporting Rate
Dashed line → Timeliness
District Ranking:
Horizontal bar chart highlighting performance disparities
Matrix Audit Table:
Monthly breakdown by district for deep analysis
Strategic Insight Panel:
Converts data into decision-ready recommendations
# Repository Structure
Health Facility Reporting.pbix – Power BI dashboard
Child_Health_Data.csv – Transformed DHIS2 dataset
Screenshots/ – Dashboard images
# How to Use
Open the .pbix file in Power BI
Use the filters panel (left) to select date range or district
Compare:
Reporting Rate (solid line)
Timeliness (dashed line)
Check:
Bottom matrix → detailed monthly performance
Right panel → strategic insights
# Key Takeaway

This project demonstrates how to bridge the gap between raw DHIS2 data and actionable public health insights, enabling more effective monitoring, faster interventions, and stronger health systems.