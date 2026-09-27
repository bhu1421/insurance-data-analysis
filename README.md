# insurance-data-analysis
End-to-end insurance data analysis and Power BI dashboard using SQL Server, Power Query and DAX.


# Insurance Data Analysis & Power BI Dashboard

## 📊 Project Overview

An end-to-end insurance data analytics project developed to analyze policy performance, premium and coverage amounts, customer segments, and claim behavior.

The dataset was stored in **Microsoft SQL Server** and then queried and loaded into **Power BI** for data preparation, modeling, DAX-based analysis, and interactive dashboard development.

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Microsoft SQL Server

## 🔄 Data Preparation

The data was cleaned and transformed using **Power Query** before analysis. This included data type standardization, handling missing values, and creating derived fields such as **Age Group** and **Customer Active/Inactive Status** to support customer and policy analysis.

Some records contain missing `ClaimDate` values. These records were retained for overall analysis but are excluded from time-based claim trend analysis where a date is required.

## 📈 Dashboard

The Power BI report consists of three interactive pages:

### Executive Overview
Provides a high-level view of policies, premiums, coverage, and claims, with breakdowns by policy type, claim status, and customer age group.

### Claims Analysis
Focuses on claim volume, claim status, claim amounts by policy type, and monthly claim trends.

### Policy & Customer Analysis
Analyzes policy distribution, policy status, customer demographics, premium and coverage metrics, and claim behavior.


## 📂 Project Structure

```text
Insurance-Data-Analysis/
│
├── README.md
├── PowerBI/
│   └── Insurance_Data_Analysis.pbix
├── Screenshots/
│   ├── executive-overview.png
│   ├── claims-analysis.png
│   └── policy-customer-analysis.png
└── Data/
    └── analysis_queries.csv
