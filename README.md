# 📦 Supply Chain Delivery Performance Analytics

An end-to-end data analytics project focused on evaluating supply chain delivery performance, identifying shipping delays, and uncovering operational patterns using **Python, SQL, and Power BI**.

This project transforms raw supply chain data into meaningful insights through data cleaning, exploratory analysis, SQL queries, and interactive dashboard visualizations.

---

## 📌 Project Overview

Efficient delivery management plays a crucial role in supply chain operations and customer satisfaction. Delays between scheduled and actual shipping durations can affect operational efficiency and delivery reliability.

This project analyzes supply chain shipping records to measure delivery performance, compare shipping modes, examine product category trends, and monitor delivery delays.

The project follows an end-to-end analytics workflow, from dataset preparation to interactive Power BI reporting.

### Project Objectives

* Clean and prepare supply chain data for analysis.
* Use SQL queries to analyze shipping and delivery performance.
* Calculate shipping delays by comparing actual and scheduled shipping durations.
* Identify delivery performance patterns across shipping modes and product categories.
* Develop an interactive Power BI dashboard to communicate key findings.
* Present data-driven insights through meaningful KPIs and visualizations.

---

## 📊 Dataset

**Dataset Name:** DataCo Smart Supply Chain for Big Data Analysis

**Dataset Source:** [Kaggle – DataCo Smart Supply Chain for Big Data Analysis](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

The original dataset contains approximately 180,519 records and 53 columns covering different aspects of supply chain operations.

For this project, relevant order, shipping, delivery status, shipping mode, and product category fields were selected for focused delivery performance analysis.

### Dataset Preparation

The dataset was processed using Python and Pandas.

Key preparation steps included:

* Selecting relevant columns for delivery performance analysis.
* Sampling 50,000 records from the selected data.
* Removing 1,699 duplicate records.
* Validating order and shipping dates.
* Checking for missing values and date inconsistencies.
* Creating calculated fields to measure shipping delays.
* Classifying shipping performance based on actual versus scheduled shipping duration.

### Final Dataset Summary

| Metric                    |          Value |
| ------------------------- | -------------: |
| Initial Sample Size       | 50,000 records |
| Duplicate Records Removed |          1,699 |
| Final Cleaned Records     |         48,301 |
| Final Number of Columns   |             10 |
| Missing Values            |              0 |

**Note:** The reported metrics and findings in this repository are based on the cleaned project dataset, not the entire original Kaggle dataset.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose                                       |
| ----------------- | --------------------------------------------- |
| Python            | Data cleaning and transformation              |
| Pandas            | Data manipulation and preprocessing           |
| SQL               | Data analysis and aggregation                 |
| Google Colab      | Python and SQL analysis workflow              |
| SQLite            | Executing SQL queries                         |
| Power BI          | Interactive dashboard development             |
| Kaggle            | Dataset source                                |
| GitHub            | Project versioning and portfolio presentation |

---

## 🔄 Project Workflow

### 1. Data Collection

Obtained the original supply chain dataset from Kaggle.

### 2. Data Cleaning

Used Python and Pandas to select relevant columns, sample records, remove duplicates, check missing values, and validate date fields.

### 3. Feature Engineering

Created calculated fields to measure shipping delays and classify delivery performance.

**Shipping Delay:**

`Shipping Delay = Actual Shipping Days - Scheduled Shipping Days`

**Shipping Performance Classification:**

* **Delayed:** Actual shipping duration exceeds the scheduled duration.
* **Ahead of Schedule:** Actual shipping duration is shorter than the scheduled duration.
* **On Schedule:** Actual shipping duration equals the scheduled duration.

### 4. SQL Analysis

Used SQL queries to examine delivery performance, shipping delays, shipping mode comparisons, product category trends, and summary metrics.

### 5. Power BI Dashboard Development

Designed a two-page interactive dashboard to present key performance indicators and delivery trends.

### 6. Insights & Reporting

Summarized key findings to understand delivery delays and variations in shipping performance across different categories.

---

## 📈 Key Performance Indicators

The following metrics were calculated from the final cleaned dataset.

| KPI                                 |    Result |
| ----------------------------------- | --------: |
| Total Records Analyzed              |    48,301 |
| Delayed Records                     |    27,720 |
| Ahead-of-Schedule Records           |    11,532 |
| On-Schedule Records                 |     9,049 |
| Shipping Delay Rate                 |    57.39% |
| Average Actual Shipping Duration    | 3.50 days |
| Average Scheduled Shipping Duration | 2.93 days |
| Average Shipping Delay              | 0.57 days |

### Shipping Performance Distribution

| Performance Category |    Records | Percentage |
| -------------------- | ---------: | ---------: |
| Delayed              |     27,720 |     57.39% |
| Ahead of Schedule    |     11,532 |     23.87% |
| On Schedule          |      9,049 |     18.73% |
| **Total**            | **48,301** |   **100%** |

*Percentages may differ slightly from 100% due to rounding.*

---

## 🔍 Key Insights

### 1. Shipping Delays

Approximately 57.39% of the analyzed records were classified as delayed when actual shipping duration exceeded scheduled shipping duration.

### 2. Actual vs. Scheduled Shipping Duration

The average actual shipping duration was 3.50 days, compared with a scheduled duration of 2.93 days. This represents an average difference of approximately 0.57 days.

### 3. Shipping Mode Performance

Shipping delay rates varied across shipping modes, indicating differences in delivery performance within the analyzed sample.

### 4. Product Category Analysis

Comparing delay rates across product categories helps identify categories that may require further investigation.

### 5. Monthly Delivery Trends

Monthly analysis provides a view of how shipping delay rates change over time.

**Analytical note:** These findings describe the selected sample and do not establish the causes of shipping delays. Further validation would be required before making operational decisions.

---

## 📊 Power BI Dashboard

The interactive Power BI report contains two pages.

### Page 1: Delivery Overview

Provides a high-level summary of delivery performance.

**Visualizations include:**

* Total Records KPI
* Delayed Records KPI
* Shipping Performance Distribution
* Monthly Delivery Delay Trend
* Delay Rate by Shipping Mode

### Page 2: Detailed Analysis

Provides a more detailed view of shipping and delivery patterns.

**Visualizations include:**

* Shipping Delay Rate by Product Category
* Actual vs. Scheduled Shipping Duration
* Delivery Status Distribution
* Product Category Slicer
* Shipping Mode Slicer
* Order Date Slicer

The dashboard enables users to explore delivery performance using interactive filters and visual comparisons.

---

## 📁 Repository Structure

```text
supply-chain-delivery-performance/
│
├── README.md
├── Supply_Chain_Analytics.ipynb
├── Supply_Chain_Cleaned_Data.csv
├── supply_chain_50000_rows_8_columns.csv
├── DescriptionDataCoSupplyChain.csv
├── power bi dashboards.pbix
├── screenshot.png
└── Screenshot ...png
```

### File Descriptions

| File                                    | Description                                                                |
| --------------------------------------- | -------------------------------------------------------------------------- |
| `README.md`                             | Project overview, methodology, tools, and findings                         |
| `Supply_Chain_Analytics.ipynb`          | Python preprocessing and SQL analysis notebook                             |
| `Supply_Chain_Cleaned_Data.csv`         | Final cleaned dataset used for analysis                                    |
| `supply_chain_50000_rows_8_columns.csv` | Intermediate dataset containing the selected columns before final cleaning |
| `DescriptionDataCoSupplyChain.csv`      | Dataset descriptions and metadata                                          |
| `power bi dashboards.pbix`              | Interactive Power BI dashboard                                             |
| `screenshot.png`                        | Dashboard screenshot                                                       |
| `Screenshot ...png`                     | Additional dashboard screenshot                                            |



---

## 🚀 How to Explore This Project

1. Review the dataset source and project overview in this README.
2. Open `Supply_Chain_Analytics.ipynb` to explore the Python data preparation and SQL analysis.
3. Review `Supply_Chain_Cleaned_Data.csv` to examine the final dataset.
4. Open `power bi dashboards.pbix` using Power BI Desktop to explore the interactive dashboard.
5. Refer to the dashboard screenshots for a quick visual preview.

---

## 🎯 Skills Demonstrated

* Data Cleaning and Preprocessing
* Data Transformation using Python and Pandas
* SQL Querying and Aggregation
* Exploratory Data Analysis
* Feature Engineering
* KPI Development
* Power BI Dashboard Design
* Data Visualization
* Analytical Thinking
* Data-Driven Reporting

---

## 📝 Conclusion

This project demonstrates an end-to-end data analytics workflow by integrating Python-based data preparation, SQL analysis, and Power BI visualization.

By transforming raw supply chain records into structured data and interactive reports, the project highlights shipping delay patterns, delivery performance differences, and opportunities for further investigation.

It showcases practical skills in data preparation, analytical querying, KPI development, and dashboard reporting.

---

## 📚 Data Source & Attribution

The original dataset is available on Kaggle:

[DataCo Smart Supply Chain for Big Data Analysis](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

Please refer to the original dataset page for its license, usage conditions, and attribution requirements.

---

**Project Category:** Data Analytics | Supply Chain Analytics | Business Intelligence

