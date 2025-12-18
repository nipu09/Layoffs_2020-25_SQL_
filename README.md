# Layoffs 2020–2025: SQL Data Cleaning Project

## 📌 Overview

This project focuses on cleaning, standardizing, and preparing a global **layoffs dataset (2020–2025)** using **SQL**. The goal is to transform raw, inconsistent data into a structured and analysis-ready format suitable for data analysis, visualization, and reporting.

This dataset can be used by:

* Data Analysts
* Data Science learners
* Researchers
* Anyone practicing SQL data cleaning techniques

---

## 📊 Dataset Description

The dataset contains company-level layoff information, including:

* Company name
* Location
* Industry
* Total laid off
* Percentage laid off
* Date of layoff
* Company stage
* Country
* Funds raised

The original data contained missing values, duplicates, inconsistent formats, and unstandardized fields, which were addressed through SQL-based cleaning steps.

---

## 🛠 Tools & Technologies Used

* **SQL (MySQL)** – for data cleaning and transformation
* **Kaggle** – dataset hosting
* **GitHub** – version control and project sharing

---

## 🧹 Data Cleaning Steps Performed

The following key cleaning operations were performed using SQL:

1. **Created staging tables** to preserve raw data integrity
2. **Removed duplicate records** using `ROW_NUMBER()` and CTEs
3. **Handled missing values** by converting blanks to `NULL`
4. **Standardized text fields** (company, industry, country)
5. **Fixed inconsistent industry labels** (e.g., Crypto variations)
6. **Converted date columns** into proper date format
7. **Validated numerical columns** (`total_laid_off`, `percentage_laid_off`)
8. **Removed unusable records** where key layoff values were missing

All transformations were done using clean, reproducible SQL queries.

---

## 📁 Files Included

* `layoffs_cleaned_2020_2025.csv` – Final cleaned dataset
* `data_cleaning.sql` – SQL script used for cleaning
* `README.md` – Project documentation

---

## 🔍 Use Cases

* Exploratory Data Analysis (EDA)
* Layoff trend analysis by year, country, or industry
* Portfolio projects for Data Analyst roles
* SQL interview preparation
* Visualization using Power BI / Tableau / Python

---

## 📈 Time Range Covered

**2020 – 2025**

---

## 📄 License

**Attribution 4.0 International (CC BY 4.0)**

You are free to:

* Share
* Adapt
* Use commercially

As long as proper credit is given to the creator.

---

## 🙋 Author

**Nipu Moni Dutta**
MCA Student | Aspiring Data Analyst

🔗 **GitHub:** [https://github.com/nipu09](https://github.com/nipu09)
🔗 **Kaggle:** [https://www.kaggle.com/nipumonidutta](https://www.kaggle.com/nipumonidutta)
🔗 **LinkedIn:** [https://www.linkedin.com/in/nipu-moni-dutta9/](https://www.linkedin.com/in/nipu-moni-dutta9/)

---

## ⭐ Acknowledgements

* Original raw dataset sourced from Kaggle
* Inspired by real-world data cleaning challenges in analytics

---

If you find this dataset useful, feel free to ⭐ it or share feedback!
