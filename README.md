# Supply Chain Delivery Performance Analytics

## 📌 Project Overview

This project analyses supply chain shipping performance to identify delivery delays, compare actual shipping duration with scheduled delivery timelines, and evaluate performance across shipping modes and product categories.

The project combines Python, SQL, and Power BI to transform raw data into meaningful insights through data cleaning, analytical queries, and interactive dashboards.

## 🎯 Objectives

* Analyse shipping delays and delivery performance.
* Compare actual shipping days with scheduled shipping days.
* Evaluate delay rates across different shipping modes.
* Investigate delivery performance by product category.
* Track monthly changes in shipping delay rates.
* Present findings through an interactive Power BI dashboard.

## 🛠️ Tools and Technologies

* Python
* Pandas
* Google Colab
* SQL
* SQLite
* Microsoft Power BI
* DAX

## 🔄 Project Workflow

1. **Data Preparation:** Selected relevant columns from the original supply chain dataset.
2. **Data Cleaning:** Removed duplicate records, validated date fields, and checked missing values.
3. **Feature Engineering:** Created Shipping Delay and Shipping Performance columns.
4. **SQL Analysis:** Analysed shipping performance, delay rates, shipping modes, and product categories.
5. **Power BI Visualisation:** Built an interactive, two-page dashboard to communicate key performance indicators and analytical findings.

## 📊 Key Findings

* **Records Analysed:** 48,301
* **Delayed Records:** 27,720
* **Shipping Delay Rate:** 57.39%
* **Average Actual Shipping Duration:** Approximately 3.50 days
* **Average Scheduled Shipping Duration:** Approximately 2.93 days
* **Average Shipping Delay:** Approximately 0.57 days

The analysis indicates that shipping delays are a significant area for further investigation.

The First Class shipping mode showed a 100% delay rate in the analysed sample. This result should be validated against the source data before drawing operational conclusions.

## 📈 Power BI Dashboard

The dashboard contains two pages:

### 1. Delivery Overview

* Total Records
* Delayed Records
* Delay Percentage
* Average Shipping Delay
* Shipping Performance Distribution
* Monthly Delivery Delay Trend
* Delay Rate by Shipping Mode

### 2. Detailed Analysis

* Product Category Analysis
* Actual vs Scheduled Shipping Duration
* Delivery Status Distribution
* Interactive slicers for product category, shipping mode, and order date

## 💡 Business Value

This analysis helps identify shipping modes and product categories that may require further investigation. The findings can support delivery performance monitoring, operational reviews, and data-driven logistics decisions.

## 📂 Project Structure

* `data/` — Cleaned dataset, if redistribution is permitted
* `notebooks/` — Python data preparation and analysis
* `sql/` — SQL analysis queries
* `powerbi/` — Power BI dashboard file
* `screenshots/` — Dashboard screenshots

## 👩‍💻 Author

Kiruthika Palanisamy
