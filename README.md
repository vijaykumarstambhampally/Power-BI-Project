# 📊 Power BI Project: Data Professional Survey Breakdown

An end-to-end Power BI project analyzing real-world survey data from 630+ data professionals to uncover insights on compensation, work-life balance, entry barriers, and preferred programming tools[span_2](start_span)[span_2](end_span).

---

## 📌 Project Overview & End-to-End Workflow
This project follows a complete Business Intelligence pipeline:
1. **Data Acquisition:** Downloaded the real survey dataset (`Data Professional Survey`) containing raw responses from industry practitioners.
2. **Data Extraction & Ingestion:** Extracted the raw dataset directly into **Microsoft Power BI Desktop**.
3. **Data Transformation (ETL in Power Query):** Cleaned, filtered, transformed columns, split delimited text fields, standardizing data types, and handled missing values.
4. **Data Loading & Modeling:** Loaded cleaned data into the Power BI Data Model and built custom DAX measures for metrics and aggregations[span_3](start_span)[span_3](end_span).
5. **Visualization & Dashboarding:** Designed and formatted an interactive single-page executive dashboard with cross-filtering visuals[span_4](start_span)[span_4](end_span).

---

## 📂 Repository Contents
* **`Data Professional Survey Breakdown.pbix`**: Interactive Power BI Desktop report containing the transformed data model, DAX calculations, and dashboard pages.
* **`Raw Data.csv`**: Raw dataset downloaded and extracted prior to Power Query ETL transformation.

---

## 🛠️ Data Cleaning & ETL Steps (Power Query)
* **Unnecessary Column Removal:** Filtered out extra administrative fields to streamline the dataset schema.
* **Text Formatting & Splitting:** Standardized salary range buckets and split multi-value columns (e.g., programming languages used).
* **Data Type Corrections:** Fixed numerical types for age, income estimates, and rating scores to enable calculations[span_5](start_span)[span_5](end_span).
* **Handling Nulls:** Standardized blank or missing responses as `Other` or `Not Specified`.

---

## 📈 Dashboard Layout & Visual Metrics (`Page 1`)

### 1. High-Level KPI Cards
* **Count of Survey Takers:** 630 total respondents[span_6](start_span)[span_6](end_span).
* **Average Age:** 29.87 years old[span_7](start_span)[span_7](end_span).

### 2. Salary Analysis by Job Title (Bar Chart)
* Evaluates average salaries across key industry roles: **Data Scientist**, **Data Engineer**, **Data Architect**, **Data Analyst**, **Database Developer**, and **Students/Job Seekers**[span_8](start_span)[span_8](end_span).

### 3. Tool & Language Preferences (Stacked Column Chart)
* Visualizes primary programming languages preferred across data roles (e.g., **Python**, **SQL**, **R**, **C/C++**)[span_9](start_span)[span_9](end_span).

### 4. Satisfaction Gauges
* **Work/Life Balance Satisfaction:** Average score of **5.74 / 10**[span_10](start_span)[span_10](end_span).
* **Salary Satisfaction:** Average score of **4.27 / 10**[span_11](start_span)[span_11](end_span).

### 5. Entry Barrier Analysis (Donut Chart)
* Measures how difficult candidates found breaking into the data industry (*Very Easy*, *Easy*, *Neither*, *Difficult*, *Very Difficult*)[span_12](start_span)[span_12](end_span).

### 6. Geographic Distribution (Treemap)
* Breaks down survey respondents by country (United States, India, United Kingdom, Canada, etc.)[span_13](start_span)[span_13](end_span).

---

## 💡 Key Findings
1. **Compensation vs. Satisfaction:** While specialized roles (Data Scientist, Data Architect) command higher average pay[span_14](start_span)[span_14](end_span), overall salary satisfaction remains low (**4.27/10**) relative to work-life satisfaction (**5.74/10**)[span_15](start_span)[span_15](end_span).
2. **Dominant Languages:** Python and SQL are by far the most popular primary languages across almost all data roles[span_16](start_span)[span_16](end_span).
3. **Industry Barriers:** A significant majority of respondents reported finding it *Difficult* or *Very Difficult* to enter the data field[span_17](start_span)[span_17](end_span).

---

## 🚀 How to View Locally
1. Download `Data Professional Survey Breakdown.pbix` from this repository.
2. Open the file using **Power BI Desktop**.
3. Explore the dashboard visuals, click on elements to test interactive cross-filtering, and review the Power Query transformation steps.
