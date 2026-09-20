# Evaluating Production Bottlenecks Through Downtime Analysis

## Project Overview

This project analyses manufacturing production data to identify the major causes of downtime, production bottlenecks, delayed batches, and operational inefficiencies.

SQL was used to explore, clean, transform, and analyse the production data, while Power BI and DAX were used to develop an interactive business intelligence dashboard for monitoring key performance indicators and identifying patterns in production downtime.

The analysis focuses on transforming operational data into actionable insights that can support production efficiency, resource planning, preventive maintenance, and management decision-making.

## Business Problem

Production downtime can reduce manufacturing efficiency, delay production schedules, increase operating costs, and affect overall productivity.

The objective of this project was to investigate production performance and answer key business questions such as:

- What are the major causes of production downtime?
- Which products experience the highest downtime frequency?
- How much downtime is related to operator versus non-operator factors?
- How does downtime change over time?
- Which operators experience the highest downtime frequency and time loss?
- Are production scheduling gaps contributing to operational delays?

## Tools & Technologies

- SQL Server
- SQL Server Management Studio (SSMS)
- Power BI
- DAX
- Data Modelling
- Data Cleaning & Transformation
- KPI Development
- Data Visualisation
- Business Intelligence

## Analysis Approach

The project followed a structured analytical process:

1. Reviewed the source tables and assessed data quality.
2. Checked record counts, missing values, and production dates.
3. Cleaned and transformed the production data using SQL.
4. Restructured downtime-factor data for analysis.
5. Joined relevant production, product, operator, and downtime information.
6. Analysed production duration, delays, downtime frequency, and root causes.
7. Compared operator-related and non-operator-related downtime.
8. Developed KPIs and interactive Power BI visualisations.
9. Translated analytical findings into operational recommendations.

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Batches Produced | 645 |
| Delayed Batches | 363 |
| Days Lost | 22 |
| Downtime Factor Instances | 885 |
| Unique Downtime Factors | 13 |
| Maximum Factors per Batch | 4 |

## Key Findings

### Downtime Root Causes

The analysis showed that **69% of downtime factors were non-operator related**, while **31% were operator related**. This indicates that most production interruptions were associated with operational and process-related factors rather than operator errors.

The most frequent downtime causes included:

- Cleaning/Sanitation — 86 occurrences
- Raw Material Shortage — 77 occurrences
- Scheduling/Coordination — 76 occurrences
- Machine Breakdown — 75 occurrences

### Product Performance

**GreenFoam Hand Soap** recorded the highest downtime frequency with **323 occurrences**, making it the most affected product in the analysis.

### Downtime Trends

Downtime increased sharply in April, declined progressively through July, and increased again in August.

March recorded the lowest downtime during the six-month analysis period, while April recorded the highest level of production disruption.

### Operator Analysis

Paul recorded the highest downtime frequency, followed by James and Emily.

The analysis also showed that the operator with the highest number of downtime events was not necessarily the operator with the highest percentage of delayed batches, highlighting the importance of analysing both frequency and proportional performance.

### Scheduling Gaps

The analysis identified potential scheduling gaps where operators were assigned to handle multiple products concurrently. This may contribute to increased downtime and reduced production efficiency.

## Business Recommendations

Based on the analysis, the following actions were recommended:

- Introduce real-time inventory monitoring and automated low-material alerts.
- Implement preventive maintenance schedules for machines associated with high downtime.
- Improve production scheduling and sequencing to minimise batch overlaps.
- Provide targeted operator training and review workload allocation.
- Conduct regular downtime reviews and introduce early-warning monitoring to support proactive decision-making.

## Business Impact

This analysis demonstrates how production data can be transformed into actionable business intelligence. By identifying the major sources of downtime and monitoring operational KPIs, manufacturing teams can prioritise improvement initiatives, strengthen production planning, reduce avoidable interruptions, and support more informed operational decisions.

## Power BI Dashboard

The interactive Power BI dashboard was developed across three analytical views to examine downtime frequency, downtime duration, and operator scheduling.

### 1. Downtime Factor Overview

![Downtime Factor Overview](01-Factor%20Overview.png)

This view provides an overview of production downtime, including delayed batches, days lost, downtime factor frequency, product-level downtime, operator-related downtime, and monthly trends.

### 2. Downtime Duration Analysis

![Downtime Duration Analysis](02-Duration%20Analysis.png)

This view analyses the duration and operational impact of downtime, including planned versus actual production time, product delay hours, time spent across downtime factors, operator downtime impact, and operator versus non-operator downtime.

### 3. Operator Scheduling

![Operator Scheduling](03-Operator%20Scheduling.png)

This view supports investigation of operator scheduling and multiple-batch activity by showing selected operators, days with multiple batches, downtime frequency, batch volumes, and detailed production records.

## Repository Contents

- `SQL` — SQL queries used for data exploration, transformation, validation, and analysis.
- `Power BI` — Interactive dashboard used to analyse production performance and downtime.
- `Presentation` — Summary of key findings, insights, and business recommendations.

## Skills Demonstrated

SQL | Power BI | DAX | Data Cleaning | Data Transformation | Data Modelling | KPI Development | Data Visualisation | Root Cause Analysis | Business Intelligence | Data Storytelling

## Author

**Collins Agyei**  
MSc Data Analytics | MBA General Management  
Data Analytics & Business Intelligence
