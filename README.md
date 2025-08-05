# task-1-data-cleaning-
Metflix Movies and TV Shows
# Netflix Data Cleaning and Preprocessing

This project involves cleaning and preprocessing the [Netflix Movies and TV Shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) to prepare it for further analysis or machine learning tasks.

---

## 📌 Objective

The objective of this task is to clean raw data by handling missing values, duplicates, inconsistent formats, and incorrect data types using Python and Pandas.

---

## 🛠️ Tools Used

- Python
- Pandas
- Jupyter Notebook / VS Code
- (Optional) Excel for manual verification

---

## 🧹 Cleaning Steps

- Removed null values from critical fields (`title`, `type`)
- Filled missing values in `country`, `rating` with `"Unknown"`
- Removed duplicate records
- Standardized text formatting (e.g., lowercasing country/type)
- Converted `date_added` to datetime format
- Renamed columns to be lowercase with underscores
- Verified and corrected column data types

