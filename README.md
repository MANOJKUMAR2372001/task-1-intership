# 🎬 Netflix Titles Data Cleaning with Pandas

## 📌 Project Overview
This project focuses on cleaning and preprocessing the **Netflix Movies & TV Shows dataset** using **Python (Pandas)**.  
The goal is to transform a raw dataset into a **clean, structured format** ready for analysis, visualization, or modeling.  

## 🎯 Objectives
- Practice **data cleaning with Pandas**.  
- Identify and fix **missing values, duplicates, and inconsistent formats**.  
- Convert raw fields (like `date_added` and `duration`) into **usable features**.  
- Build confidence in handling raw datasets independently.  

## 🛠 Tools Used
- Python  
- Pandas  
- NumPy  

## 🧹 Cleaning Steps
1. **Loaded dataset** and inspected shape, columns, and missing values.  
2. **Standardized column names** (lowercase, underscores).  
3. **Removed duplicates** (entire rows and duplicate `show_id`).  
4. **Handled missing values**:  
   - Filled `director`, `country`, `rating` with `"Unknown"`.  
   - Dropped rows missing essential info (`title`, `type`).  
5. **Converted `date_added`** to datetime + extracted `year`, `month`, and `day`.  
6. **Split `duration`** into `duration_int` (numeric) and `duration_type` (`minutes` / `seasons`).  
7. **Extracted features**:  
   - `primary_country` (first listed country).  
   - `primary_cast` (first listed cast member).  
8. **Created final cleaned dataset** with new engineered columns.  

## 📂 Deliverables
- `netflix_titles.csv` → Raw dataset  
- `netflix_titles_cleaned.csv` → Cleaned dataset  
- `notebooks/cleaning_steps.ipynb` → Step-by-step Pandas cleaning process  

## 📈 Results
- **Original dataset:** 8,807 rows × 12 columns  
- **Final cleaned dataset:** 8,807 rows × 21 columns  
- Ready for **Exploratory Data Analysis (EDA)**, visualization, or ML tasks.  

---

✨ This project highlights the **importance of preprocessing** as the first step in any data science workflow.
