# 📊 E-Commerce Analytics & Executive Dashboard

## Overview

This project demonstrates an end-to-end E-Commerce Analytics solution designed to help business stakeholders monitor sales performance, understand customer behavior, and make data-driven decisions.

The solution integrates SQL, Python, Power BI, Excel, and DAX to build a scalable analytics pipeline covering data warehousing, customer segmentation, KPI reporting, and sales forecasting.

The project simulates a real-world business intelligence workflow used by e-commerce organizations to track revenue, customer retention, product performance, and future sales trends.

---

## Business Problem

E-commerce businesses generate large volumes of transactional data daily. Without a centralized analytics system, organizations face challenges such as:

* Slow report generation
* Lack of visibility into customer behavior
* Inefficient inventory planning
* Difficulty identifying high-value customers
* Limited forecasting capabilities

This project addresses these challenges by creating a complete analytics solution that transforms raw transactional data into actionable business insights.

---

## Objectives

* Build a scalable SQL data model for e-commerce transactions.
* Automate data cleaning and transformation processes.
* Perform customer segmentation using RFM analysis.
* Generate executive-level KPIs for business monitoring.
* Forecast future sales using ARIMA time-series modeling.
* Develop an interactive Power BI dashboard for decision-makers.

---

## Tech Stack

| Technology   | Purpose                              |
| ------------ | ------------------------------------ |
| Python       | Data Cleaning, Analysis, Forecasting |
| SQL          | Data Modeling & ETL                  |
| Pandas       | Data Manipulation                    |
| Scikit-Learn | Customer Segmentation                |
| Statsmodels  | ARIMA Forecasting                    |
| Power BI     | Dashboard Development                |
| DAX          | KPI Calculations                     |
| Excel        | Data Validation & Reporting          |

---

## Project Architecture

```text
Raw Data
   ↓
SQL ETL Pipeline
   ↓
Sales Fact Table
   ↓
Python Data Processing
   ↓
RFM Segmentation + KPI Generation + Forecasting
   ↓
Power BI Dashboard
   ↓
Business Insights
```

---

## Dataset Structure

### Orders Dataset

| Column     |
| ---------- |
| OrderID    |
| CustomerID |
| ProductID  |
| OrderDate  |
| Quantity   |
| UnitPrice  |

### Customers Dataset

| Column       |
| ------------ |
| CustomerID   |
| CustomerName |
| Region       |
| SignupDate   |

### Products Dataset

| Column      |
| ----------- |
| ProductID   |
| ProductName |
| Category    |

---

## Key Features

### 1. Automated ETL Pipeline

* Data ingestion using SQL
* Fact table generation
* Revenue calculation
* Automated transformation workflow

### 2. Customer Segmentation

RFM Analysis:

* Recency
* Frequency
* Monetary Value

Customers are grouped into behavioral segments using K-Means clustering.

Example Segments:

* Champions
* Loyal Customers
* Potential Loyalists
* At-Risk Customers
* Lost Customers

---

### 3. Executive KPI Reporting

Generated KPIs include:

* Gross Merchandise Value (GMV)
* Total Orders
* Total Customers
* Average Order Value (AOV)
* Revenue Growth Rate
* Category Contribution
* Regional Revenue
* Customer Lifetime Value (LTV)

---

### 4. Sales Forecasting

Implemented ARIMA Time-Series Forecasting:

* Historical Sales Analysis
* Trend Detection
* Seasonality Identification
* Future Revenue Prediction

Evaluation Metric:

* Mean Absolute Percentage Error (MAPE)

---

## Dashboard Features

### Executive Overview

* Total Revenue
* Total Orders
* Total Customers
* Revenue Growth %
* Average Order Value

### Customer Analytics

* Customer Segmentation
* Repeat Purchase Analysis
* Customer Lifetime Value

### Product Analytics

* Top Products
* Top Categories
* Revenue Contribution

### Regional Analytics

* Revenue by Region
* Orders by Region
* Regional Performance Comparison

### Forecasting Dashboard

* Historical Revenue Trend
* Forecasted Revenue
* Monthly Growth Analysis

---

## Key Business Insights

The analytics framework enables businesses to:

* Identify high-value customer segments.
* Detect customer churn risks.
* Optimize marketing strategies.
* Improve inventory planning.
* Track product performance.
* Monitor regional sales trends.
* Support executive decision-making through real-time KPIs.

---

## Project Structure

```text
ecommerce-analytics-dashboard/
│
├── data/
├── sql/
├── src/
├── notebooks/
├── dashboard/
├── outputs/
├── requirements.txt
├── main.py
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/ecommerce-analytics-dashboard.git
```

Navigate to project directory:

```bash
cd ecommerce-analytics-dashboard
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run Project

Execute the complete pipeline:

```bash
python main.py
```

Pipeline Steps:

1. Data Cleaning
2. Revenue Calculation
3. RFM Segmentation
4. KPI Generation
5. Sales Forecasting
6. Dashboard Data Export

---

## Sample Outputs

Generated Files:

```text
outputs/
│
├── customer_segments.csv
├── executive_kpis.csv
└── sales_forecast.csv
```

---

## Future Enhancements

* Customer Churn Prediction
* Product Recommendation System
* Real-Time Dashboard Integration
* Azure Data Factory ETL
* Snowflake Data Warehouse
* Streamlit Analytics Portal
* Machine Learning-Based Demand Forecasting
* Automated Email Reporting

---

## Author

Shrashti Maurya

B.Tech – Computer Science Engineering

Aspiring Data Analyst | Business Analyst | Analytics Engineer

Skills: SQL, Python, Power BI, Excel, Machine Learning, Data Visualization

---

## License

This project is licensed under the MIT License.
