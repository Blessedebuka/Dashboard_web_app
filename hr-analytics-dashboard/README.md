Title: Executive HR Analytics and Attrition Dashboard

Project Overview: An end-to-end Human Resources reporting solution built in Power BI to monitor active headcount, evaluate compensation trends, track employee satisfaction, and perform deep-dive risk analysis on voluntary and involuntary employee turnover.

Data Architecture & Modeling

Built a robust Star Schema data model to optimize query performance and reporting relationships.

Dimension Tables: Dim_Departments, Dim_Employees, Dim_Manager, Dim_Position

Fact & Measure Tables: Fact_table connected cleanly to a dedicated measure_table handling all custom DAX calculations.

Dashboard Pages & Key Metrics

1. Active Headcount Page
Core KPIs: Tracks total active employees (207), average salary ($69.02K), average employee age (46.98), and overall satisfaction score (3.89).

Dimensional Slicers: Dynamic filtering by employment status and salary tier.

Departmental Breakdown: Visualizes headcount distribution and average salary tiers across departments like Production, IT/IS, Sales, and Administration.

2. Attrition Analysis Page
Turnover Insights: Analyzes total terminated employees, overall attrition rate (33.44%), and voluntary attrition rate (28.30%).

Risk Breakdown: Includes a comprehensive Manager Risk Analysis table to identify attrition trends by reporting lines.

Satisfaction & Trends: Correlates attrition rates with satisfaction tiers and maps monthly termination spikes over time.
