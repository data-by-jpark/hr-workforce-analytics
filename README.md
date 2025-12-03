# HR Workforce Analytics Project

This repository contains a two-part HR Workforce Analytics project that transforms a raw HR employee dataset into a clean, reliable foundation for workforce insights, exploratory data analysis (EDA), and ultimately a **Tableau HR Workforce Dashboard**.

Although I previously led an **HR data analysis project using real employee data** in my former workplace, that data is confidential and cannot be shared publicly.  

To demonstrate the same analytical workflow—and to showcase my expanded skillset in Python, data cleaning, and HR analytics—I rebuilt the entire project using a **public Kaggle HR dataset** that resembles real-world HRIS (Human Resources Information System) data. This version reflects not only the approach I applied professionally, but also the enhanced techniques and best practices I have developed since then.

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
- Exporting a fully cleaned, analysis-ready dataset (cleaned_employee_data.csv)

---

### 📊 Notebook 2 — HR Workforce EDA  
**Location:** `notebooks/02_workforce_eda.ipynb`  
**Status:** 🛠 In Progress

This notebook explores the cleaned dataset to uncover key HR insights, including:

- Workforce composition & demographics  
- Headcount, hiring, and turnover trends  
- Tenure distribution & employment lifecycle patterns  
- Segment analysis by business unit, department type, job title, etc.  
- Data visualization using Python plotting libraries  

> Notebook 2 is actively being developed, using the cleaned dataset generated in Notebook 1. It will serve as the foundation for building the Tableau HR Workforce Dashboard.

---

## 📈 Next Steps — Tableau HR Workforce Dashboard

After completing data cleaning and EDA, the final phase of this project is developing a **Tableau HR Workforce Dashboard** featuring:

- Headcount trends  
- Attrition & retention metrics  
- Tenure distribution  
- Workforce demographics  
- Department and job segmentation  
- Key HR analytics KPIs used in real organizations  

The goal is to deliver an interactive, executive-friendly dashboard that enables strategic workforce decision-making.

---

## 📂 Repository Structure

```
project/
├── data/
│   ├── cleaned_employee_data.csv
│   ├── raw_employee_data.csv
│   └── README.md                     # dataset source & licensing info
├── notebooks/
│   ├── 01_data_cleaning_preprocessing.ipynb
│   └── 02_workforce_eda.ipynb        # in progress          
├── README.md                         # you are here
└── requirements.txt
```

---

## 📎 Dataset Source & Licensing

- Dataset obtained from Kaggle  
  (_Employee Dataset — CC0: Public Domain_)
- Licensing, details, and source information can be found in:  
  `data/README.md`
- Raw data should only be uploaded if redistribution complies with the dataset license.

---

## 🚀 About This Project

This project showcases:

- End-to-end data cleaning using Python
- HRIS-style data validation and preprocessing
- Workforce analytics logic and feature engineering
- Exploratory data analysis with real HR metrics
- A clean, portfolio-friendly project workflow
- Preparation for a Tableau HR Workforce Dashboard
- A reproducible public-data version of the HR analytics project I previously led using confidential real employee data  

If you're a recruiter or reviewer, feel free to explore the notebooks in order.

---
