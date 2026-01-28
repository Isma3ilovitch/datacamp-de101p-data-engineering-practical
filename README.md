# DataCamp Data Engineer Certification (DE101P) – Practical Exam

This repository contains my solution to the **Practical Exam (DE101P)** for the **Data Engineer Certification** from **DataCamp**.

The project focuses on **cleaning, transforming, and merging multiple real-world datasets** into a single, analysis-ready table using Python.

---

## 📌 Project Overview

**Company context:**  
1001-Experiments is a health-tech company that provides personalized supplements based on user health data collected from wearable devices and health apps.

The data engineering task is to **reliably integrate multiple data sources** so data scientists and product teams can work with a unified dataset.

---

## 🗂️ Datasets Used

The project works with four datasets:

- `user_health_data.csv`  
  Daily health metrics, habits, and wearable device data

- `supplement_usage.csv`  
  Supplement intake records per user

- `experiments.csv`  
  Metadata about supplement experiments

- `user_profiles.csv`  
  User demographic and profile information

Each dataset contains identifiers that must be correctly aligned and validated during merging.

---

## ⚙️ Task Objective

Create a Python function:

```python
merge_all_data(
    user_health_data_path,
    supplement_usage_path,
    experiments_path,
    user_profiles_path
)
```
---
## The function must:

-Clean and validate the input datasets

-Handle missing and inconsistent values

-Merge all datasets correctly

-Return one Pandas DataFrame

-Match exact column names and definitions required by the exam

This function is designed to be executed directly by the evaluator without modification.

---
## 🧠 Skills Demonstrated

-Data cleaning and preprocessing

-Multi-table joins and data integration

-Handling real-world data inconsistencies

-Writing reusable and testable Python functions

-Pandas best practices

-Data engineering thinking (not just analysis)

---
## 🛠️ Tech Stack

-Python

-Pandas

-Jupyter Notebook

---

## 📜 Certification

This project was completed as part of the DataCamp Data Engineer Certification – Practical Exam (DE101P).

