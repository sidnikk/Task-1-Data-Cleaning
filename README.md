# Task 1: Data Cleaning and Preprocessing

## 📄 Dataset
**Customer Personality Analysis**  
Source: [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

## 📌 Objective
To clean a raw dataset by:
- Handling missing values
- Removing duplicates
- Standardizing inconsistent formatting
- Renaming columns
- Fixing data types

## ⚙️ Tools Used
- Python
- Pandas
- Google Colab

## 🧹 Steps Performed
1. Loaded the dataset using `pandas.read_csv()`
2. Checked for missing values using `.isnull().sum()`
3. Filled missing values in `Income` with the column mean
4. Removed duplicates using `.drop_duplicates()`
5. Standardized text fields (e.g., `Education`) to lowercase
6. Converted `Dt_Customer` to datetime format
7. Renamed column headers to lowercase with underscores
8. Exported cleaned dataset to `cleaned_dataset.csv`

## 📂 Files Included
- `raw_dataset.csv`: Original file
- `cleaned_dataset.csv`: Cleaned and final version
- `cleaning_script.py`: Python script used
- `README.md`: Summary of task and learnings

## 🧠 Learning Outcomes
- Data cleaning with Pandas
- Handling real-world data issues
- Preprocessing pipeline for analysis and modeling
