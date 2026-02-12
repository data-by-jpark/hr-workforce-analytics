# HR Workforce Analytics Project

This repository contains a comprehensive, **three-part HR Workforce Analytics project**. It demonstrates the end-to-end transformation of raw HRIS data into a clear, executive-level staffing strategy.

## Project Purpose & Professional Context
This project is a professional-grade replication of the workforce analytics workflows I designed and led during my tenure at the **Ontario Public Service (OPS)**.

Because the original government data is confidential, I have rebuilt this workflow using a public dataset. This project serves two purposes:
1. **Replication**: Demonstrating the rigorous reporting standards required in a high-level government environment.
2. **Skill Growth**: Showcasing my improved technical skills in Python, data engineering, and strategic forecasting developed since my time at OPS.

---

## 🚀 The 3-Part Project Journey
This project is structured into three distinct phases to replicate a real-world business intelligence cycle.

### Phase 1: Data Engineering & Preprocessing
**Location:** `notebooks/01_data_cleaning_preprocessing.ipynb`  
**Status:** ✅ Completed

**Goal**: Transform raw HR records into a validated, analysis-ready foundation.

- **Rigorous Cleaning**: Resolved inconsistencies across `EmployeeStatus`, `ExitDate`, and `TerminationType`, and removed outliers.
- **Feature Engineering**: Created essential HR metrics like `IsActive`, `AttritionFlag`, `TenureDays`, and `Age`.
- **Standardization**: Ensured the dataset met the quality standards required for senior leadership reporting.

### Phase 2: Exploratory Data Analysis (EDA) & Strategy 
**Location:** `notebooks/02_workforce_eda.ipynb`  
**Status:** ✅ Completed

**Goal**: Diagnose organizational "pain points" and engineer tactical solutions.

- **Workforce Risk Analysis**: Identified a "double-sided" risk where **32.4% of staff are nearing retirement (55+)**, while new hires (under 1 year) show high turnover, threatening a significant loss of institutional knowledge.
- **Growth & Attrition Trends**: Diagnosed the "Inflow vs. Outflow" of staff to explain the recent headcount declines observed in 2024 and 2025.
- **Tactical Staffing Solutions**: Engineered a **Conversion Pipeline** to identify **254 eligible contractors** for permanent roles, providing a data-driven way to stabilize the workforce and reduce hiring costs.

### Phase 3: Tableau HR Workforce Dashboard
**Location:** [Link to Tableau Public](https://public.tableau.com/views/HRWorkforceDashboardPresentFuture/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**Status:** 🛠 In Progress

**Goal**: Translate complex Python findings into a visual, interactive experience for stakeholders.

- **Executive Summary**: High-level KPIs for Headcount and Attrition.
- **Strategic Deep-Dives**: Filterable views for department-specific turnover and retirement forecasting.
- **Actionable Visuals**: A "Conversion Pipeline" tracker for operational management.

---

## 💡 Key Strategic Insights
- **The Growth Gap**: Analysis revealed that departures began outpacing hiring in early 2024, leading to the current shrinking workforce.
- **Stabilization Opportunity**: Instead of costly external recruiting, the data proves that 254 proven contractors are ready for immediate conversion.
- **Knowledge Bridge**: Recommendations include a mentorship program to pass veteran knowledge to new hires before the 32% retirement wave hits.

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
│   └── 02_workforce_eda.ipynb        
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

## 🛠️ Technical Toolkit

-  **Languages:** Python (Pandas, NumPy)
-  **Visualization:** Matplotlib, Seaborn, Tableau
-  **Analysis:** Workforce Risk Mapping (Retirement), Tenure-based Attrition Diagnostics, Contract-to-Permanent Pipeline Forecasting
-  **Tools:** Jupyter Notebook, Kaggle, GitHub

---

## 📬 Contact & Feedback

If you are a recruiter or a data professional, I’d love to hear your thoughts on this workflow. Feel free to reach out via [LinkedIn](www.linkedin.com/in/jay-park-8a88b3193) or open an issue in this repository.
