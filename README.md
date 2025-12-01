# HR Workforce Analytics Project

This repository contains a two-part HR Workforce Analytics project focused on transforming a raw HR employee dataset into a clean, reliable foundation for workforce insights and exploratory data analysis (EDA).

The dataset was sourced from Kaggle and cleaned extensively to resemble a real-world HRIS export.

---

## 📘 Project Notebooks

### 📒 Notebook 1 — Data Cleaning & Preprocessing  
**Location:** `notebooks/01_data_cleaning_preprocessing.ipynb`  
**Status:** ✅ Completed

This notebook prepares the raw HR dataset for analysis by:

- Inspecting raw data quality (missing values, data types, duplicates)  
- Cleaning and standardizing date fields, categorical fields, and identifiers  
- Fixing inconsistencies across `EmployeeStatus`, `ExitDate`, and `TerminationType`  
- Handling missing, incorrect, or outlier values (e.g., unrealistic DOBs)  
- Creating core derived fields:  
  - `IsActive`  
  - `AttritionFlag`  
  - `TenureDays`  
  - `Age`  
  - `SameDayTermination`  
- Exporting a fully cleaned, analysis-ready dataset  

---

### 📊 Notebook 2 — HR Workforce EDA  
**Location:** `notebooks/02_workforce_eda.ipynb`  
**Status:** 🛠 In Progress

This notebook explores the cleaned dataset to uncover workforce insights, including:

- Workforce composition & demographics  
- Headcount, hiring, and turnover trends  
- Tenure distribution & employment lifecycle patterns  
- Segment analysis by business unit, department type, job title, etc.  
- Data visualization using Python plotting libraries  

> Notebook 2 is actively being developed, using the cleaned dataset generated in Notebook 1.

---

## 📂 Repository Structure

project/
│
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ └── 02_workforce_eda.ipynb # in progress
│
├── data/
│ ├── cleaned_employee_data.csv
│ └── README.md # dataset source & licensing info
│
├── README.md # you are here
│
└── requirements.txt

---

## 📎 Dataset Source & Licensing

The dataset was obtained from Kaggle.  
For licensing and usage restrictions, see: `data/README.md`.  
*Raw data should only be uploaded if the license permits redistribution.*

---

## 🚀 About This Project

This project showcases:

- End-to-end data cleaning for HRIS-style datasets  
- Workforce analytics preparation and reasoning  
- A clean, portfolio-ready notebook workflow  
- Practical preprocessing steps used in real HR analytics teams  

If you're a recruiter or reviewer, feel free to explore the notebooks in order.

---
