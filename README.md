# COVID-19 Data Analysis & Visualization

A Python-based data analysis project that processes global COVID-19 data to uncover trends, identify the most impacted countries, and visualize case distributions using `pandas`, `matplotlib`, and `seaborn`.

## 📊 Project Overview

This repository contains the implementation of a data analysis workflow designed to handle, clean, and visualize pandemic tracking metrics. The objective is to extract meaningful insights from a structured time-series dataset through statistical aggregations and data visualizations.

### Key Objectives
*   **Data Preprocessing:** Handle datetime conversions and structure verification.
*   **Global Trend Analysis:** Track total confirmed cases over time to visualize the global curve.
*   **Demographic Insights:** Identify and highlight the top 10 most severely impacted countries based on the latest available data.
*   **Advanced Visualization:** Construct a density/distribution heatmap of cases across major regions over time.

---

## 💾 Dataset

The analysis utilizes the public COVID-19 dataset available on Kaggle.
*   **Source:** [Kaggle - COVID-19 Virus Report](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)
*   **Target File:** `covid_19_clean_complete.csv`

---

## 🛠️ Tech Stack & Dependencies

This project relies on the core Python data science library stack:

*   **Python 3.x**
*   **pandas** - For data loading, datetime parsing, pivot profiling, and aggregations.
*   **matplotlib** - For structural line graphs and customized bar charts.
*   **seaborn** - For generating high-density distribution heatmaps.

To install the required libraries, run:
```bash
pip install pandas matplotlib seaborn
