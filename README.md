## Sierra Leone Health Facility Reporting & Data Quality Dashboard ((DHIS2-Based))

# Project Summary
This project analyzes health facility reporting performance in Sierra Leone using data exported from DHIS2.

The dashboard evaluates two critical public health data quality indicators:

Reporting Completeness
Reporting Timeliness

The project was designed to support Monitoring & Evaluation (M&E) teams, NGOs, and Ministries of Health in identifying reporting gaps, strengthening data reliability, and improving operational decision-making.

By transforming raw DHIS2 exports into interactive analytics dashboards, the project demonstrates how health information systems can support evidence-based public health management.

# Public Health Problem

In many countries, DHIS2 serves as the backbone of national health reporting systems. Healthcare facilities submit routine monthly reports used for:

Disease surveillance
Resource allocation
Program monitoring
Public health evaluation

However, raw DHIS2 exports are often:

wide-format and difficult to analyze,
inconsistent across districts,
and lacking immediate visibility into reporting failures.

Without effective analytics systems, delayed or incomplete reporting can weaken healthcare planning and reduce the reliability of operational decision-making.

This project demonstrates how data analytics can bridge the gap between raw reporting data and actionable public health intelligence.

# Project Objectives
Assess reporting completeness across districts and facilities
Monitor reporting timeliness trends over time
Identify underperforming districts and facilities
Detect operational reporting gaps and inconsistencies
Build an interactive dashboard for M&E workflows
Support data quality assessment and reporting supervision

# Dataset Information
## Data Source

DHIS2-exported health facility reporting datasets

## Key Variables
District

Health Facility

Reporting Period

Reporting Status

Completeness Rate

Timeliness Rate

## Data Format
CSV

Excel

# Tools & Technologies Used
Power BI

Power Query

DAX

DHIS2

Excel

# Data Cleaning & Transformation
1. Data Extraction (DHIS2)
Exported aggregated reporting data from DHIS2

Focused on facility-level reporting indicators across districts

2. Data Transformation (Power Query)
The preprocessing workflow involved:

Converting wide-format DHIS2 exports into long-format analytical tables using unpivoting

Cleaning and standardizing the district and date fields

Preparing datasets for time-series analysis

Structuring reporting metrics for dashboard integration

# Data Modeling & Analysis
DAX Measures Created
Completeness Rate (%)

Timeliness Rate (%)

Reporting Gap = Completeness − Timeliness

National average KPIs

District performance rankings

The analysis focused on identifying operational reporting weaknesses and visualizing reporting consistency across facilities and districts.

# Dashboard & Visualizations
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/75bddbe6-289e-441d-aa3b-dfe809d14db5" />



# Key Insights
1. National Reporting Decline

Reporting performance peaked at approximately 97% in August 2025, followed by a significant decline during Q4.

This pattern may indicate:

system outages,
staffing challenges,
training gaps,
or operational disruptions.
2. District-Level Performance Disparities

Districts such as Kono and Bonthe consistently performed below national targets, while districts such as Moyamba and Kenema maintained reporting rates above 90%.

This suggests uneven reporting capacity and operational performance across districts.

3. Reporting Behavior Patterns

Strong alignment between completeness and timeliness metrics suggests the possibility of batch data entry workflows rather than continuous real-time reporting.

4. Operational Monitoring Value

The dashboard improves visibility into:

delayed submissions,
incomplete reporting,
and district-level reporting instability.

This supports faster interventions and improved health system supervision.

# Recommendations
Strengthen reporting supervision in underperforming districts

Implement automated reporting reminders and validation checks

Improve district-level training and support for reporting workflows

Conduct regular data quality audits

Introduce early-warning monitoring systems for delayed reporting

# Repository Structure
Health Facility Reporting. pbix – Power BI dashboard
Child_Health_Data.csv – Transformed DHIS2 dataset
Screenshots/ – Dashboard images

# How to Use
Open the .pbix file in Power BI

Use dashboard filters to select:
reporting period,
district,
or facility

Compare:
reporting completeness,
timeliness trends,
and district performance

Review the matrix audit table for detailed monthly reporting analysis

Use the strategic insights panel for decision-support recommendations

# Why This Project Matters

This project demonstrates how healthcare analytics can transform raw DHIS2 reporting data into actionable public health intelligence.

The dashboard supports:

Monitoring & Evaluation (M&E)

Data Quality Assessment (DQA)

Health systems strengthening

Operational performance monitoring

Evidence-based decision-making

It reflects real-world public health analytics workflows commonly used in NGOs, Ministries of Health, and international health programs.

# Potential Extensions
Facility-level anomaly detection

Integration with GIS mapping for spatial analysis

Predictive modeling of reporting delays

Automated reporting quality alerts

Multi-country comparative reporting analysis
# Key Takeaway

This project demonstrates how to bridge the gap between raw DHIS2 data and actionable public health insights, enabling more effective monitoring, faster interventions, and stronger health systems.

# Author
June Wangari Kamau

Health Data Analyst | Public Health & M&E Analytics Enthusiast
