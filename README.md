# NASA-WISE-Near-Earth-Object-Discovery-Analytics
Transformed raw NASA WISE mission discovery data into clear metrics and dashboards. Analyzed Near-Earth Asteroid and comet discoveries using Python and SQL, and visualized trends with Tableau to support scientific insight and data-driven decision-making.
Perfect — here is a **complete, professional README.md** you can copy-paste directly into your GitHub repo.
This is written at a **NASA / government / professional internship level**, not student fluff.

---

# 🚀 NASA WISE Near-Earth Object Discovery Analytics

## 📌 Project Overview

This project analyzes public NASA data from the **WISE/NEOWISE mission** to explore discovery statistics of **Near-Earth Asteroids (NEAs)** and comets.
The goal is to transform raw scientific discovery data into **clear metrics, visualizations, and dashboards** that provide insight into object classifications and discovery patterns.

This project demonstrates core **data analytics skills** including data cleaning, analysis, SQL querying, and dashboard creation using real NASA datasets.

---

## 🎯 Problem Statement

NASA collects large volumes of observational data from space missions like WISE.
However, raw discovery data alone is difficult to interpret without structured analysis.

**This project addresses the problem of:**

> Turning raw NASA Near-Earth Object discovery data into decision-ready insights through metrics, analysis, and visualization.

---

## 🔍 Research Questions

This project answers the following key questions:

1. What types of objects (NEAs vs comets) are being discovered by the WISE mission?
2. How many objects have been discovered in total?
3. What are the relative proportions of different object types?
4. What are the typical characteristics of discovered objects?
5. How can raw scientific data be transformed into clear, interpretable insights?

---

## 📊 Dataset

* **Source:** NASA Open Data Portal
* **Dataset:** WISE NEA / Comet Discovery Statistics
* **Format:** CSV
* **Access:** Public, no authentication required

🔗 Dataset link:
[https://data.nasa.gov/dataset/wise-nea-comet-discovery-statistics](https://data.nasa.gov/dataset/wise-nea-comet-discovery-statistics)

---

## 🧰 Tech Stack

### Programming & Analysis

* **Python 3**
* **Pandas** – data cleaning and manipulation
* **NumPy** – numerical operations
* **Matplotlib / Seaborn** – data visualization

### Data Storage & Querying

* **SQLite**
* **SQL** – aggregation and metric queries

### Visualization

* **Tableau Public** – dashboard creation and storytelling

### Tools

* **JupyterLab** – interactive analysis
* **Git & GitHub** – version control and project sharing
* **macOS** – development environment
* **Python Virtual Environment (`venv`)** – dependency isolation

---

## 🧠 Methodology

### 1. Data Ingestion

* Load the NASA CSV dataset directly from the official data source.

### 2. Data Cleaning

* Inspect columns and data types
* Handle missing values
* Standardize column names
* Prepare the dataset for analysis

### 3. Analysis & Metrics

* Calculate total discoveries
* Aggregate counts by object type
* Generate summary statistics
* Identify distributions and patterns

### 4. SQL Querying

* Store cleaned data in a SQLite database
* Run SQL queries to aggregate and filter data

### 5. Visualization & Dashboard

* Create charts showing object classifications and distributions
* Build a Tableau dashboard to present key insights clearly

---

## 📈 Key Metrics

* Total number of objects discovered
* Discovery count by object type
* Percentage breakdown of NEAs vs comets
* Summary statistics of selected parameters

---

## 📊 Dashboard

The final dashboard presents:

* Discovery counts by object type
* Summary KPIs
* Visual distributions for quick interpretation

*(Dashboard screenshots included in the `/dashboard` folder.)*

---

## 📁 Project Structure

```
nasa-nea-analytics/
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
│   └── analysis.ipynb
├── sql/
│   └── queries.sql
├── dashboard/
│   └── screenshots/
├── README.md
```

---

## ✅ Results & Insights

* The majority of objects discovered by WISE fall into specific object classifications.
* Clear metrics make it easier to interpret discovery outcomes compared to raw data tables.
* Visual dashboards help communicate scientific findings to non-technical stakeholders.

---

## 🎓 Skills Demonstrated

* Data cleaning and preparation
* Exploratory data analysis
* SQL querying and aggregation
* Dashboard creation
* Working with real NASA data
* Professional documentation

---

## 📎 Notes

This project uses **publicly available NASA data** and is intended for **educational and portfolio purposes**.

---
