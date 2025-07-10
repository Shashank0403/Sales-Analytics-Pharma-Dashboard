# Sales-Analytics-Pharma-Dashboard

## 🔍 Project Overview

This project transforms raw sales data into actionable insights using Power BI. The data represents sales activity from distributors covering the German and Polish markets. The company doesn't directly sell to consumers but relies on a network of distributors who share retail-level sales data in CSV format.

---
## 🧰 Skills Used

**Power BI** • **DAX** • **Power Query** • **Python** • **SQL** • **Data Analytics** • **Data Visualization** • **ETL** • **Data Modeling** • **Business Intelligence** • **Dashboard Design** • **Stakeholder Communication**
---

## ✨ Key Features

- Built using **Power BI Desktop**
- Data cleaning and transformation via **Power Query Editor**
- Published and accessible via **Power BI Service**
- Fully **interactive multi-page report**
- Supports dynamic filtering (by year, month, product, and more)

---

## 📌 Objectives

The goal is to deliver a data-driven story that meets the analytical needs of different business stakeholders:

| For | Key Insights |
|-----|--------------|
| Executive Committee | High-level performance summaries by year, month, region, channel, sub-channel, and product. Identify top-performing drug classes, products, and cities. |
| Sales Managers & Reps | In-depth distributor and customer analysis, including top-performing products, clients, and regions. Sales breakdown by channel and sub-channel. |
| Head of Sales | Team performance review with drill-down views on sales by team, manager, rep, and product class. Ability to filter data by time period. |

---

## 📂 Dataset Summary

Data was obtained from distributor reports and includes wholesale-retail transactions. Below is a snapshot of the key fields:

| Field | Description |
|-------|-------------|
| Distributor | Name of the wholesaler |
| Customer Name | Buyer’s name |
| City / Country | Customer location |
| Channel / Sub-channel | Type of buyer (Hospital, Pharmacy, Gov, Private) |
| Product Name / Class | Drug and its classification |
| Quantity / Price / Sales | Units sold, unit price, and total sales |
| Sales Rep / Manager / Team | Sales hierarchy |
| Month / Year | Date of transaction |

---

## 🧠 Analytical Approach

| Requirement | Solution |
|-------------|----------|
| Executive Overview | Created a dashboard showing year-over-year trends, top-performing products and cities, and a sales breakdown by channels |
| Distributor/Customer Insights | Visualized detailed sales trends for each distributor and customer, with filters for deep dives |
| Sales Team Performance | Developed a performance tracker for sales teams with rankings and contribution breakdowns |

---

## 🔎 Exploratory Data Analysis (EDA)

Performed initial data checks using **Python (pandas)** to:

- Identify missing or invalid values
- Detect outliers (e.g., negative sales)
- Classify columns into numerical and categorical types
- Understand the structure and consistency of the dataset

(Details available in `data-exploration.ipynb`)

---

## 🧹 Data Cleaning & Transformation

Executed using **Power Query** in Power BI:

- Renamed columns for clarity
- Fixed data types
- Structured the data into a star schema with one fact table and several dimension tables

[Data Model] <img width="1512" height="856" alt="image" src="https://github.com/user-attachments/assets/2d4eab34-3c02-4399-8279-445484118478" />

---

## 📊 Dashboard Breakdown

### 1️⃣ Sales Analytics

A top-level snapshot of overall performance, ideal for C-level stakeholders.

<img width="1166" height="645" alt="image" src="https://github.com/user-attachments/assets/357aa285-6cff-4e42-b820-0cec13c7b579" />

---

### 2️⃣ Partner & Customer Evaluation

Dig into distributor-level performance, customer trends, and product-level insights.

<img width="1163" height="661" alt="image" src="https://github.com/user-attachments/assets/72154b5c-bdf4-46e5-a5a9-78cb3dcb101f" />

---

### 3️⃣ KPI Performance - Sales Team

Track sales contribution by team, manager, and rep. Filter by product and time period for precise evaluation.

<img width="1164" height="665" alt="image" src="https://github.com/user-attachments/assets/72eebe8e-818d-4ffc-9659-3d1ce10d9670" />

---
