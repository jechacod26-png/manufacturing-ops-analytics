# Manufacturing Operations Analytics

## Production, Quality & Inventory Optimization using Python

Project Overview

This project presents an end-to-end data analytics solution for a manufacturing assembly environment, focused on improving production performance, quality control, and inventory management through data-driven decision making.

The analysis integrates operational data such as planned vs actual production, downtime, scrap, defects, and material consumption, and translates insights into actionable recommendations and quantified business impact.

Objectives

- Identify variability drivers in production performance.

- Detect critical quality issues using Pareto analysis.

- Prioritize operational problems based on impact.

- Simulate improvement scenarios and estimate benefits.

- Design and validate an inventory replenishment policy (ROP + Safety Stock).

## Methodology

The project follows a structured analytics pipeline:

- Data Preparation

- Synthetic but realistic manufacturing data (daily, by line and shift).

- Key operational KPIs: yield, scrap %, plan adherence, downtime.

- Exploratory Data Analysis (EDA)

- Planned vs actual production trends.

- Performance comparison by production line.

- Weekly scrap analysis.

- Quality Analysis

- Pareto analysis of defect types.

- Identification of “vital few” defects driving scrap.

## Anomaly Detection

- Isolation Forest to detect atypical operational events.

- Prioritization of days/shifts with high downtime and low adherence.

## Inventory Optimization

Demand estimation based on production output.

Safety Stock and Reorder Point (ROP) calculation.

Inventory simulation under lead time variability.

Scenario Simulation

Conservative operational improvement scenario (+3% output).

Impact on production volume, demand, and inventory policy.

Business Impact Estimation

Translation of production gains into economic impact using a conservative unit margin assumption.

Key Insights

A small number of defect types concentrate most of the scrap (Pareto behavior).

High downtime events strongly correlate with low plan adherence.

Operational improvements generate different returns depending on the production line scale and variability.

Inventory policies must be adjusted when production capacity improves to avoid stockouts.

## Recommendations

Prioritize downtime reduction initiatives on high-impact production lines.

Focus quality improvement efforts on dominant defect categories.

Implement formal inventory replenishment policies based on ROP and Safety Stock.

Review demand and lead time parameters periodically as operations evolve.

## Tools & Technologies

- Python

- pandas, numpy

- matplotlib

- scikit-learn (Isolation Forest)

- Jupyter Notebook

# Notes

Data used in this project is simulated to replicate real manufacturing behavior.

The analytical approach is directly transferable to real plant data.

Value Proposition

This project demonstrates how manufacturing data can be transformed into operational decisions with measurable impact, bridging the gap between analytics and day-to-day production management.
[Manufacturing_Data_Analytics_Project_Production,_Quality_&_Inventory_Optimization_with_Python.ipynb](https://github.com/user-attachments/files/25080726/Manufacturing_Data_Analytics_Project_Production._Quality_._Inventory_Optimization_with_Python.ipynb)
[Data_Analytics.pdf](https://github.com/user-attachments/files/25080814/Data_Analytics.pdf)
