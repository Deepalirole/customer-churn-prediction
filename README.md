📊 Customer Churn Analysis Dashboard using Power BI

This Power BI dashboard project helps visualize and analyze customer churn data. It offers insights into why customers are leaving, their contracts, internet service type, tenure, and how you can reduce churn using actionable metrics. The dashboard also includes a "What-If Analysis" ROI Sandbox to simulate savings from targeted retention strategies.


🚀 Dashboard Preview
Executive Overview

Churn Drivers

Segments Analysis

Action Center

ROI Sandbox (What-If)

📌 Project Objectives

Understand and visualize customer churn patterns.

Identify key drivers contributing to churn.

Perform segment-wise analysis.

Use DAX measures to create calculated columns, KPIs, and parameters.

Build interactive visuals for actionable insights.

Simulate retention impact using a What-If Analysis ROI model.

✅ Features

Churn rate by contract type

Churn rate by internet service

Customer demographics by region and tenure

Tickets per 100 customers

Root cause of churn using Key Influencers

Interactive What-If analysis: Predict ROI based on save rates and cost


🛠 Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query

Advanced Filters and Slicers

Parameters and What-If Analysis

Optional: Excel/CSV for data preprocessing


📊 Step-by-Step Implementation

Data Collection

Imported customer churn dataset (can be a .csv or Excel file).

Cleaned null values and inconsistencies using Power Query Editor.

Data Transformation

Created calculated columns like Tenure Group, Churn Clean, etc.

Created measures using DAX (e.g., churn rate %, total charges, tickets per 100 customers).

Data Modeling

Defined relationships between tables (if applicable).

Created necessary hierarchies and dimensions.

Building the Dashboard

Page 1: Executive Overview (KPI cards, churn by contract/internet/location).

![image_alt](https://github.com/Deepalirole/customer-churn-prediction/blob/955358c8d55a72403724e731bb4df5225a643564/Screenshot%202025-08-28%20130700.png)

Page 2: Why They Leave (Funnel view, Key Influencers, tickets by attributes).
![image_alt](https://github.com/Deepalirole/customer-churn-prediction/blob/0da659fe08eb6216ef26b9f3fa182fb30fe845a8/Screenshot%202025-08-28%20130719.png)

Page 3: Segments (Contract-wise churn %, avg charges, churn % across tenure).
![image_alt](https://github.com/Deepalirole/customer-churn-prediction/blob/b5062950b1c759beab9a4e125d4db8cf19f28427/Screenshot%202025-08-28%20130737.png
)
Page 4: Action Center (Detailed data view with filters and reason codes).

Page 5: ROI Sandbox (What-If simulation using parameters and calculated values).

Customization

Applied themes, data labels, and tooltips for clarity.

Added filters and slicers for drill-down and dynamic view.
