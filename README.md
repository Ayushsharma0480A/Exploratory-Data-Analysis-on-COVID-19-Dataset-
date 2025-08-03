# Exploratory-Data-Analysis-on-COVID-19-Dataset-
Hello LinkedIn Family! I just completed a comprehensive EDA project on COVID-19 data using Python, Pandas, Matplotlib, and Seaborn
# 🦠 COVID-19 Data Analysis (EDA Project)

This project presents an Exploratory Data Analysis (EDA) on global COVID-19 datasets, including death statistics and vaccination data. The goal is to clean, merge, and analyze the data to uncover patterns, missing values, and country-level health insights.

---

## 📁 Dataset Source

- COVID-19 Death and Vaccination data from [Our World in Data](https://ourworldindata.org/)
- Datasets used:  
  - `covid-deaths.csv`  
  - `covid-vaccinations.csv`

---

## 📌 Project Goals

- Understand the structure and missing values of the datasets.
- Merge datasets to create a comprehensive COVID analysis dataset.
- Clean and drop unnecessary or highly missing features.
- Visualize data distribution and country-wise trends.

---

## ⚙️ Technologies Used

- **Python** (Jupyter Notebook)
- **Libraries**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

## 📊 Key Steps in the Notebook

- 📌 **Missing Values Visualization:**  
  Using `sns.heatmap` to explore missing data across columns.

- 🧹 **Data Cleaning & Feature Selection:**  
  - Removed columns with more than 45% missing values.
  - Kept only meaningful columns related to COVID spread, healthcare metrics, and demography.

- 🔁 **Dataset Merge:**  
  Combined the deaths and vaccine datasets using `pd.merge()` with `how='outer'`.

- 📈 **Visualizations:**  
  - Histograms of continuous variables
  - Country-wise distribution analysis
  - Trends in new cases, deaths, reproduction rate, etc.

---

## 🧾 Columns Kept for Analysis

```text
'continent', 'location', 'date', 'population',
'total_cases', 'new_cases', 'total_deaths', 'new_deaths',
'reproduction_rate', 'stringency_index', 'population_density',
'median_age', 'gdp_per_capita', 'diabetes_prevalence',
'hospital_beds_per_thousand', 'life_expectancy'

