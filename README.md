# 💼 Data Jobs & Salary Analytics Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Dataset-Jobs%20in%20Data-blue?style=for-the-badge&logo=kaggle&logoColor=white" alt="Dataset" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status" />
</p>

---

## 📌 Table of Contents
* [Overview](#-overview)
* [Key Business Insights](#-key-business-insights)
* [Dashboard Preview](#-dashboard-preview)
* [Core Interactive Features](#-core-interactive-features)
* [Data Pipeline & Structure](#-data-pipeline--structure)
* [How to Access & Run](#-how-to-access--run)
* [Future Roadmap](#-future-roadmap)

---

## 🔎 Overview
An interactive Power BI dashboard analyzing global compensation trends, job role demand, experience level impact, and remote work dynamics across the modern data industry.

> [!NOTE]
> Powered by `jobs_in_data.csv` and built in Power BI Desktop to provide prospective and working data professionals with data-driven salary benchmarks.

---

## 💡 Key Business Insights

* **Top Compensated Roles:** Visual comparison of median compensation across Data Science, Machine Learning, Data Engineering, and Analytics.
* **Experience Curve:** Quantifying the salary progression from Entry-Level (EN) and Mid-Level (MI) to Senior (SE) and Executive (EX).
* **Workplace Model Impact:** Comparing earnings across Remote, In-Person, and Hybrid work arrangements worldwide.
* **Geographical Distribution:** Tracking employee distribution and market compensation disparity by company location.

---

## 🖥️ Dashboard Preview

<p align="center">
  <img src="Screenshot%202026-07-02%20114217.png" alt="Data Jobs and Salary Dashboard Preview" width="950" />
</p>

---

## ⚡ Core Interactive Features

* **Multi-Filter Slicers:** Filter metrics dynamically by Job Category, Experience Level, Work Setting, and Year.
* **Interactive Tooltips:** Hover over regional maps and bar charts for detailed salary percentiles and job counts.
* **Cross-Filtering Visuals:** Selecting a specific job title updates geographic compensation distributions and experience cards instantly.

---

## 🗂️ Data Pipeline & Structure

<details>
<summary><b>Click to expand dataset architecture & transformation steps</b></summary>

<br>

### 1. Source Dataset (`jobs_in_data.csv`)
* `work_year`: Year when the salary was paid.
* `job_title`: Specific data specialization title.
* `job_category`: Broad domain grouping (Data Science, Data Analysis, etc.).
* `salary_currency` & `salary_in_usd`: Standardized currency normalization.
* `experience_level`: Entry-level, Mid-level, Senior, Executive.
* `employment_type`: Full-time, Part-time, Contract, Freelance.
* `work_setting`: Remote, In-Person, Hybrid.
* `company_location` & `company_size`: Geographic region and workforce scale.

### 2. Power Query Transformations
* Standardized salary values to USD for uniform cross-border comparison.
* Grouped niche job roles into standardized categories.
* Replaced abbreviated codes (e.g., `EN`, `SE`, `FT`) with descriptive business labels.

</details>

---

## 🚀 How to Access & Run

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/rohitpatil261003/Data_Jobs_And_Salarly_Analysis.git](https://github.com/rohitpatil261003/Data_Jobs_And_Salarly_Analysis.git)
