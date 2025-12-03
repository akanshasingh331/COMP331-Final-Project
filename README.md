# **COMP331 Final Project – Data Quality Analysis (Retail Data Warehouse)**

## Overview**

This repository contains the full analysis, code, visualizations, and final written report for my **COMP331 – Data Quality Final Project** at the University of the Fraser Valley.

The project evaluates data quality issues within a real-world **Retail Data Warehouse**, using weekly sales, store attributes, and regional indicators collected across **45 stores** over multiple years.
The objective is to apply concepts from **Week 10 (Data Warehousing)** and **Week 11 (Data Mining)** to assess the dataset using key Data Quality dimensions.

---

## Project Objectives**

* Apply **data warehousing concepts** such as ETL, star schema design, and referential integrity.
* Evaluate the dataset using **three major Data Quality dimensions**:

  * **Completeness**
  * **Consistency**
  * **Validity**
* Identify specific data quality issues with evidence from real data.
* Propose actionable recommendations to improve ETL and warehouse quality.
* Generate static and animated visualizations using Python.
* Produce a strict **2-page final report** following assignment guidelines.

---

## Repository Contents**

| File                                                                     | Description                                                            |
| ------------------------------------------------------------------------ | ---------------------------------------------------------------------- |
| `COMP331_Final_2PAGE_TNR15_HEADER.docx`                                  | **Final 2-page report** (Times New Roman, 1.5 spacing, 1-inch margins) |
| `Retail_DQ_Report.pdf`                                                   | Full narrative report generated from Python                            |
| `Retail_DQ_Report_with_charts.pdf`                                       | Report including charts & analysis                                     |
| `untitled1.py`                                                           | Main Google Colab Python script used for analysis                      |
| `sales data-set(in).csv`, `stores data-set.csv`, `Features data set.csv` | Retail datasets used for analysis                                      |
| `missing_features.csv`                                                   | Missing-value summary exported through code                            |
| `avg_sales_by_type.csv`                                                  | Processed dataset used for sales visualizations                        |
| `holiday_vs_nonholiday_animation.gif`                                    | Animated holiday vs non-holiday sales visualization                    |
| `holiday_vs_nonholiday_sales.csv`                                        | Aggregated sales dataset                                               |
| `README.md`                                                              | Repository documentation (this file)                                   |

---

## Methods & Tools Used**

### Languages & Libraries**

* Python (pandas, numpy)
* matplotlib & seaborn
* matplotlib.animation (GIF creation)
* FPDF (PDF report generation)
* Google Colab

### Data Quality Techniques Applied**

* Missing value analysis (MarkDown1–5)
* Uniqueness & duplicate detection
* Warehouse grain validation
* Referential integrity testing (Store IDs)
* Date format standardization and validation
* Temporal alignment checks between fact/dimension tables
* Numeric range and validity checks
* ETL-style transformations and cleaning

---

##  Visualizations Produced**

The analysis includes both static and animated visualizations:

✔ Missingness in MarkDown1–5
✔ Holiday vs Non-Holiday Sales comparison
✔ Distribution of Weekly Sales
✔ Animated line chart of Weekly Sales over time
✔ Animated bar chart showing evolving holiday effects

These visualizations help highlight data quality issues and retail patterns.

---

##  Final Report Submission**

The final 2-page project report required by the instructor is included:

📄 **COMP331_Final_2PAGE_TNR15_HEADER.docx**
Contains:

* ¼ page Introduction
* 1 page Data Quality Analysis
* ½ page Recommendations
* ¼ page Conclusion
* References on separate page

This document strictly follows:

* Times New Roman 12 pt
* 1.5 spacing
* 1-inch margins
* EXACT 2-page limit

---

##  How to Reproduce the Analysis**

1. Open `untitled1.py` in **Google Colab**.
2. Upload the three dataset files:

   * `sales data-set(in).csv`
   * `stores data-set.csv`
   * `Features data set.csv`
3. Run the notebook to:

   * Perform all data quality checks
   * Generate all charts and GIFs
   * Export PDF reports

---

## Author**

**Akansha Singh**
University of the Fraser Valley
COMP331 – Data Quality
Instructor: **Amir Daneshpajouh**

---

##  Contact**

For questions or feedback, feel free to connect through GitHub.

