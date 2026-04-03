# 🏥 Healthcare Data Analysis using SQL

## 📌 Overview

This project demonstrates an end-to-end data analysis workflow using PostgreSQL.
It involves cleaning a real-world healthcare dataset, handling data inconsistencies, and extracting meaningful insights using SQL.

---

## ⚙️ Tools & Technologies

* PostgreSQL
* SQL
* Microsoft Excel (Data Cleaning)

---

## 📊 Dataset

* File: `healthcare_dataset.csv`
* Records: 55,000+
* Contains patient information such as age, gender, hospital, billing amount, admission type, and medical details

---

## 🔥 Key Challenges Solved

* Fixed PostgreSQL installation and connection issues
* Cleaned messy CSV data (extra columns, inconsistent headers)
* Handled data type mismatches during import
* Successfully imported large dataset into database

---

## 📈 Analysis Performed

* Total patient count
* Gender-wise distribution
* Average and highest billing analysis
* Top hospitals based on patient volume
* Admission type distribution

---

## 📊 Key Insights

* Majority of patients fall within the 30–50 age group
* Certain hospitals handle significantly higher patient loads
* Billing amounts vary widely across cases
* Emergency admissions form a significant portion of total cases

---

## 🚀 How to Run

1. Import dataset into PostgreSQL using `\COPY`
2. Execute queries from `analysis.sql`
3. Analyze results using pgAdmin

---

## 📷 Results

Screenshots of query outputs are available in the `/screenshots` folder

---

## 🧠 Learning Outcome

This project helped me understand real-world data challenges, debugging SQL errors, and building structured analytical queries.

---

## 🔗 Repository Structure

* `dataset/` → Raw dataset
* `queries/` → SQL queries
* `screenshots/` → Output images
* `README.md` → Project documentation
