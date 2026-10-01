# Insurance Data Analysis & Power BI Dashboard

An end-to-end insurance data analytics project using **Microsoft SQL Server, Power Query, DAX, and Power BI** to analyze policy performance, customer segments, premiums, coverage, and claims.

## 🔗 Published Power BI Report

👉 **[View Interactive Power BI Dashboard](https://app.powerbi.com/groups/0a334a76-91ec-49cf-93ab-6def0cdbad56/reports/4206f312-4448-4ad6-91fd-3756ce354845/3425d00b5381c017137c?experience=power-bi&bookmarkGuid=75e3f5af91c1504012dc)**

---

## 📊 Project Overview

This project analyzes insurance policy and claims data to understand:

- Policy distribution and performance
- Premium and coverage amounts
- Customer demographics and segmentation
- Claim volume, status, and amounts
- Policy and claim behavior across different customer and policy segments

The data is stored in **Microsoft SQL Server** and loaded into **Power BI**, where it is prepared, modeled, analyzed using DAX, and presented through an interactive three-page dashboard.

---

## 🛠️ Tools & Technologies

- **Microsoft SQL Server** — Data storage and querying
- **Power Query** — Data cleaning and transformation
- **Power BI** — Interactive dashboard development
- **DAX** — Analytical measures and calculations
- **Data Modeling** — Relationships between customer, policy, date, and claims data

---

## 🔄 Data Preparation

Data preparation was performed using **Power Query** before analysis.

Key preparation steps included:

- Data type standardization
- Handling missing values
- Creating analytical fields such as **Age Group**
- Creating **Customer Active/Inactive Status**
- Preparing policy and claims data for analysis

Some records contain missing `ClaimDate` values. These records are retained for overall analysis but are excluded from time-based claim trend analysis where a valid date is required.

---

## 🧩 Data Model

The project uses a relational data model connecting customer, policy, date, and claims information to support interactive analysis in Power BI.

The model enables analysis across:

- Customers
- Policies
- Claims
- Dates
- Policy types
- Customer demographics

---

## 📐 DAX & Analysis

DAX measures were developed to support analysis of:

- Policy counts
- Premium amounts
- Coverage amounts
- Claim volumes
- Claim amounts
- Claim outcomes
- Customer and policy-level metrics

These measures are used throughout the dashboard to provide dynamic results based on selected filters.

---

## 📈 Power BI Dashboard

The Power BI report contains **three interactive pages**.

### 1. Executive Overview

Provides a high-level view of the insurance portfolio, including:

- Policy performance
- Premium amounts
- Coverage amounts
- Claim information
- Policy type distribution
- Claim status
- Customer age-group analysis

### 2. Claims Analysis

Focuses on claim-related performance and behavior, including:

- Claim volume
- Claim status
- Claim amounts by policy type
- Monthly claim trends
- Claim-related segmentation

### 3. Policy & Customer Analysis

Provides deeper analysis of:

- Policy distribution
- Policy status
- Customer demographics
- Premium and coverage metrics
- Customer segmentation
- Claim behavior across customer and policy segments

---

## 🖼️ Dashboard Preview

### Executive Overview

![Executive Overview](1 Executive-Overview.png)

### Claims Analysis

![Claims Analysis](Screenshots/claims-analysis.png)

### Policy & Customer Analysis

![Policy & Customer Analysis](Screenshots/policy-customer-analysis.png)

---

## 📂 Project Structure

```text
Insurance-Data-Analysis/
│
├── README.md
│
├── PowerBI/
│   └── Insurance_Data_Analysis.pbix
│
├── Screenshots/
│   ├── executive-overview.png
│   ├── claims-analysis.png
│   └── policy-customer-analysis.png
│
└── Data/
    └── analysis_queries.csv
