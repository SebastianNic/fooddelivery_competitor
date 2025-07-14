# 📊 Competitor Analysis Dashboard for Food Delivery Services

## 🧭 Overview

This project presents a competitive analysis between our food delivery service called Mjam and its main competitor, focusing on a selected region defined by multiple ZIP codes. The analysis was visualized in an interactive Tableau dashboard using order data collected over a two-month period.

## 🎯 Objective

The goal of this analysis is to:

• Compare monthly order volumes between Mjam and its competitor.

• Measure and visualize growth compared to the previous month.

• Track the number of active restaurants per service.

• Show the regional distribution of restaurant activity and orders.

• Provide quick, actionable insights via a clean and interactive Tableau dashboard.

## 🗃️ Data Sources

Two main datasets, provided as xlsx, were used for each service:

#### Mjam Data:

One dataset containing two columns for both months with order data for each restaurant, as well as multiple columns for loacation related data for each restaurant.

#### Competitor Data:

Two datasets, one for each month, only containing the restaurants with a ZIP code and the amount of orders each.

## 🌍 Regional Scope

The analysis focuses on a **specific geographic area**, defined by a set of ZIP codes. All data was filtered to include only restaurants operating within this region.
The set of ZIP codes was the following: 8010, 8020, 8036, 8041, 8042, 8043, 8045, 8051, 8052, 8053, 8054, 8055, 8063, 8077

## 📈 Dashboard Features

Built using Tableau, the dashboard includes the following elements:

🏪 Count of active restaurants by service incl. MoM growth rate

📉 Monthly comparison of total orders (Mjam vs. competitor) incl. MoM growth rate

📊 List of best performing restaurants of competitor and the according performance metric for Mjam

🗺️ Regional distribution of restaurants and order volume

## 🛠️ Tools & Technologies

• Tableau for dashboard creation and visualization

• Python & Pandas for data preprocessing

• Excel/CSV files as input sources

## Repository Structure
```
├── data/
│   ├── input/   
│   │   ├── Food Delivery.xlsx - Master Report Monthly (1).csv
│   │   ├── Comp_data.xlsx - Month 1.csv
│   │   └── Comp_data.xlsx - Month 2.csv
│   ├── preprocessed/
│   │   ├── us_formatted_month_1 (1).csv
│   │   ├── us_formatted_month_2 (1).csv
│   │   ├── comp_formatted_month_1.csv
│   │   └── comp_formatted_month_2.csv
├── pictures/
│   └── Food_Delivery_Comparison_Dashboard.png
├── notebooks/
│   └── Mjam_Food_Delivery_Data_Preperation.ipynb
└── README.md
```

## ▶️ How to View the Dashboard

Use the following link to view the dashboard in Tableau Public:

.............



