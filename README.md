# Government Procurement Intelligence & Risk Analytics

An end-to-end Data Analytics project that analyzes Government e-Marketplace (GeM) procurement data using Microsoft Excel and SQL. The project focuses on transforming raw procurement data into actionable business insights through data cleaning, feature engineering, KPI development, SQL analysis, and interactive dashboard reporting.

The objective is to simulate a real-world analytics workflow by identifying procurement trends, monitoring payment performance, evaluating operational efficiency, and supporting data-driven decision-making.

---

# Table of Contents

- Project Overview
- Business Problem
- Objectives
- Dataset
- Technology Stack
- Project Workflow
- Repository Structure
- Data Preparation
- Feature Engineering
- Business KPIs
- SQL Analysis
- Dashboard
- Business Insights
- Project Roadmap
- Future Enhancements
- Skills Demonstrated
- How to Use This Repository
- Author

---

# Project Overview

Government procurement involves thousands of purchase orders across ministries, departments, organizations, and buyers. Although the data contains valuable operational and financial information, extracting meaningful insights requires systematic cleaning, transformation, and analysis.

This project demonstrates an end-to-end analytics workflow by preparing procurement data for analysis, developing business metrics, performing SQL-based analysis, and creating an executive dashboard for procurement monitoring.

The project is designed to reflect the responsibilities of a Data Analyst or Business Analyst in a real-world business environment.

---

# Business Problem

Large procurement datasets make it difficult for decision-makers to quickly answer important business questions such as:

- How much procurement has been completed?
- Which organizations account for the highest procurement spending?
- Which buyers manage the largest procurement values?
- How much payment is still outstanding?
- Which contracts represent the highest financial risk?
- What procurement trends exist over time?
- Which operational processes require improvement?

This project answers these questions using Excel and SQL.

---

# Objectives

The objectives of this project are to:

- Prepare raw procurement data for analysis.
- Clean and validate procurement records.
- Create meaningful business and operational metrics.
- Perform SQL-based business analysis.
- Build an interactive Excel dashboard.
- Identify procurement and payment risks.
- Generate actionable business insights.

---

# Dataset

Source:
Government e-Marketplace (GeM)

The dataset includes procurement information such as:

- Ministry
- Department
- Organization
- Office Name
- Contract Number
- Buyer Name
- Buyer Designation
- Order Amount
- Due Payment
- Bill Status
- Order Date
- Delivery Date
- Invoice Date
- CRAC Date
- Payment Mode
- Order Type

The dataset represents real-world procurement records and is used solely for educational and portfolio purposes.

---

# Technology Stack

| Technology | Purpose |
|------------|---------|
| Microsoft Excel | Data Cleaning, Feature Engineering, Dashboard Development |
| SQL | Business Analysis and Reporting |
| Git | Version Control |
| GitHub | Project Documentation and Portfolio |

Future enhancements will include:

- Power BI
- DAX
- Python (Pandas)
- Machine Learning

---

# Project Workflow

```
Raw GeM Procurement Dataset
            │
            ▼
Data Cleaning and Validation
            │
            ▼
Feature Engineering
            │
            ▼
SQL Database
            │
            ▼
Business Analysis
            │
            ▼
Interactive Dashboard
            │
            ▼
Business Insights
```

---

# Repository Structure

```
government-procurement-analytics/
│
├── README.md
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── excel/
│
├── sql/
│
├── reports/
│
├── screenshots/
│
└── docs/
```

---

# Data Preparation

The procurement dataset is cleaned and prepared for analysis using Microsoft Excel.

The data preparation process includes:

- Converting the dataset into structured Excel Tables.
- Formatting numeric and date fields.
- Validating data quality.
- Standardizing text values.
- Creating SQL-ready datasets.
- Preserving raw data separately from cleaned data.

This ensures that the analytical dataset is accurate, consistent, and ready for reporting.

---

# Feature Engineering

Additional analytical columns are created to improve business reporting.

Features include:

- Outstanding Payment Percentage
- Payment Completion Percentage
- Amount Paid
- Order Year
- Order Quarter
- Order Month
- Delivery Time
- Invoice Delay
- CRAC Delay
- Procurement Value Category
- Pending Payment Category
- High Value Procurement Flag
- Payment Risk Classification
- Delivery Risk Classification
- Overall Procurement Risk

These derived metrics provide additional business context that is not available directly from the raw dataset.

---

# Business KPIs

The project develops business KPIs including:

- Total Procurement Value
- Total Due Payment
- Total Contracts
- Total Organizations
- Total Buyers
- Average Contract Value
- Average Delivery Time
- Payment Completion Rate
- Outstanding Payment Percentage
- Procurement by Ministry
- Procurement by Department
- Procurement by Buyer
- Procurement by Organization
- High Risk Contracts
- Procurement Category Distribution

These KPIs support procurement monitoring and executive reporting.

---

# SQL Analysis

The SQL analysis answers important business questions, including:

- What is the total procurement value?
- What is the total outstanding payment?
- Which organizations have the highest procurement spend?
- Which buyers manage the highest procurement value?
- Which departments have the largest pending payments?
- What are the monthly procurement trends?
- What is the average contract value?
- Which organizations have zero outstanding payments?
- Which buyers have the highest pending payments?
- How are procurement values distributed across categories?

The SQL scripts demonstrate aggregation, filtering, grouping, ranking, and business reporting techniques.

---

# Dashboard

The Excel dashboard provides an interactive summary of procurement performance.

Dashboard components include:

- KPI Cards
- Pivot Tables
- Pivot Charts
- Interactive Slicers
- Procurement Trends
- Organization-wise Analysis
- Ministry-wise Analysis
- Buyer Performance
- Outstanding Payment Analysis
- Procurement Distribution

Dashboard screenshots will be added after project completion.

---

# Business Insights

The project aims to generate insights such as:

- Identify organizations with the highest procurement expenditure.
- Highlight buyers managing high-value contracts.
- Detect organizations with significant outstanding payments.
- Compare procurement performance across ministries and departments.
- Evaluate procurement efficiency using payment and delivery metrics.
- Classify contracts based on procurement risk.
- Support data-driven procurement decisions through business reporting.

---

# Project Roadmap

## Phase 1

- Project Planning
- Data Understanding
- Data Cleaning
- Data Validation

## Phase 2

- Feature Engineering
- KPI Development
- Data Preparation

## Phase 3

- SQL Database Creation
- SQL Business Queries
- Business Analysis

## Phase 4

- Excel Dashboard
- Executive Reporting
- Business Recommendations

## Phase 5

- GitHub Documentation
- Project Portfolio

## Phase 6 (Future)

- Power BI Dashboard
- DAX Measures
- Python Automation
- ETL Pipeline
- Machine Learning-Based Risk Prediction

---

# Future Enhancements

Future versions of this project will include:

- Interactive Power BI dashboards.
- Advanced DAX calculations.
- Automated data cleaning using Python.
- ETL pipeline development.
- Procurement risk prediction using machine learning.
- Interactive reporting with drill-through capabilities.

---

# Skills Demonstrated

This project demonstrates practical experience in:

### Data Analytics

- Data Cleaning
- Data Validation
- Feature Engineering
- Data Transformation

### Microsoft Excel

- Pivot Tables
- Pivot Charts
- Lookup Functions
- Conditional Formatting
- Slicers
- Dashboard Design

### SQL

- Data Import
- Aggregations
- GROUP BY
- CASE Statements
- Ranking
- Business Reporting
- Query Optimization

### Business Intelligence

- KPI Development
- Dashboard Development
- Data Visualization
- Business Analysis
- Executive Reporting


This project has been developed for educational and portfolio purposes. The dataset is sourced from Government e-Marketplace (GeM) procurement records. Any analysis, conclusions, or recommendations presented are intended solely to demonstrate data analytics techniques and should not be interpreted as official government findings or policy recommendations.
