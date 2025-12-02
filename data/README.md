# Dataset Information

This folder contains the raw and cleaned datasets used in the **HR Workforce Analytics Project**.

The dataset was sourced from Kaggle and is released under the **CC0: Public Domain** license, which allows free use, modification, and redistribution — including uploading to GitHub.

---

## 📎 Source

**Kaggle Dataset:**  
Employee/HR Dataset (All in One)
https://www.kaggle.com/datasets/ravindrasinghrana/employeedataset

**License:**  
**CC0: Public Domain**  
- Free for personal and commercial use  
- Redistribution allowed  
- No attribution required (but the source is referenced here for transparency)

---

## 📂 Files in This Folder

data/
│
├── raw_employee_data.csv # Original Kaggle dataset (raw, unmodified)
├── cleaned_employee_data.csv # Cleaned dataset generated in Notebook 1
└── README.md # This file

---

## 📘 Notes on Usage

- The **raw dataset** is included because its CC0 license permits redistribution.  
- The **cleaned dataset** is produced in Notebook 1 and is the primary input for Notebook 2 (EDA).  
- The dataset contains synthetic/non-identifiable HR records intended for learning and analytics practice.  
- All preprocessing steps — including data cleaning, date standardization, HR logic alignment, and derived variable creation — are documented in `01_data_cleaning_preprocessing.ipynb`.
