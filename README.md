# 🚗 Automotive Sales Performance Dashboard

## 📊 Project Overview

This project analyzes automotive sales performance using Microsoft Power BI.

The dashboard was designed to help sales management monitor revenue, gross profit,
sales volume, target achievement, regional performance, and individual salesman
performance.

The project demonstrates how raw sales data can be transformed into an interactive
business intelligence dashboard and converted into actionable business insights.

---

## 🎯 Business Problem

Sales management needs a faster and more effective way to:

- Monitor sales performance
- Compare actual sales against targets
- Identify top and underperforming salespeople
- Analyze regional sales performance
- Monitor monthly sales trends
- Identify performance gaps
- Support data-driven sales decisions

Previously, these analyses could require multiple manual reports.

This project provides an interactive dashboard that brings these analyses together
in one place.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Clean and prepare automotive sales data.
2. Build a structured data model.
3. Create sales performance KPIs.
4. Analyze salesman performance.
5. Analyze regional performance.
6. Compare target vs actual sales.
7. Build an interactive Power BI dashboard.
8. Generate business insights and recommendations.

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modeling
- Data Visualization
- Business Intelligence

---

## 🧹 Data Preparation

The data preparation process included:

- Data cleaning
- Removing/handling inconsistent values
- Standardizing data types
- Preparing date fields
- Preparing salesman reference data
- Preparing region reference data
- Preparing model reference data
- Preparing monthly target data

Power Query was used to transform the data before loading it into Power BI.

---

## 🏗️ Data Model

The Power BI model uses a fact-and-dimension structure.

### Fact Tables

- Sales Transaction
- Monthly Target

### Dimension / Reference Tables

- Date
- Month
- Salesman
- Region
- Model

The relationships were designed to allow consistent filtering and analysis across
different dimensions.

---

## 📐 Key KPIs

### Total Revenue

Measures the total sales value generated.

### Gross Profit

Measures the profitability based on revenue and estimated cost.

### Total Unit

Measures the actual number of vehicles sold.

### Target Unit

Represents the planned sales volume.

----

## 📊 Achievement & Variance

**Achievement %**

Achievement % digunakan untuk mengukur tingkat pencapaian actual sales terhadap target.

**Formula:**

> Achievement % = Actual Unit ÷ Target Unit × 100%

**Variance Unit**

Variance menunjukkan selisih antara actual sales dan target.

> Variance Unit = Actual Unit − Target Unit

**Interpretasi:**

- 🟢 **Achievement ≥ 100%** → Target tercapai atau terlampaui
- 🟡 **Achievement 90%–99%** → Mendekati target
- 🔴 **Achievement < 90%** → Perlu perhatian dan improvement

---

## 👨‍💻 Author

**Djusran**

Data Analyst | Sales & Automotive Business

Project: **Automotive Sales Performance Dashboard**
