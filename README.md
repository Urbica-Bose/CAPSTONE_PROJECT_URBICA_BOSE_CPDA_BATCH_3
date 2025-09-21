Hospital Performance Insights (Hero Vired Capstone)



📌 Project Overview

This project analyzes the performance of 5,300+ hospitals across key domains (Mortality, Safety, Readmissions) to identify high-performing hospitals and highlight areas needing improvement. An interactive Power BI dashboard was developed to help stakeholders visualize hospital performance, drill into details, and run What-If analyses to simulate improvement scenarios.



🎯 Objectives

Evaluate hospital performance across critical domains.

Provide interactive visualizations for exploration at hospital, state, and domain levels.

Enable scenario simulation to assess the impact of improvement strategies.

Deliver actionable insights for stakeholders through storytelling and executive reporting.

🗂 Data & Processing

Source: Hospital_General_Information.csv

Cleaning Steps:

Handled nulls and “Not Available” values

Standardized column names

Converted percentages into numeric fractions

Normalized categorical values (State, Hospital Type, Ownership)

Modeling:

Built a star-like schema with two key tables:

Hospital_General_Information (hospital attributes)

Perf_Long (unpivoted performance data by domain)

Relationship: Facility ID (1) → Perf_Long[Facility ID] (many)

📊 Features & Measures

Core KPIs: % Better / No Different / Worse (per domain), Avg Rating, % High-Performing Hospitals

Scenario parameters: Rating Threshold and Measure Improvement

Scenario projections: Simulated the effect of converting “Worse” outcomes into “Better/No Different”

📈 Visualizations (8 Pages in Power BI)

Overview – KPIs, slicers

Geographic Analysis – Choropleth maps + Top states

What-If Analysis – Scenario testing

Performance Measures – Drill-through matrix & charts

Hospital Detail – Hospital-level profiles

Scenario Insights – Projections & impact analysis

🔑 Insights

Even a 10–20% shift in “Worse” measures to “Better/No Different” can significantly increase the number of hospitals classified as High-Performing.

State-level and ownership-based comparisons reveal clusters of underperformance and excellence.

📦 Deliverables

HeroVired_Capstone_PBIX.pbix (Power BI Report)

Hospital_General_Information.csv (Dataset)

DAX_measures.txt (All DAX calculations with comments)

Presentation.pptx (Executive summary & storytelling)

Requirements_Checklist.pdf (Validation & documentation)
