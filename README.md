# 🚗 Vehicle Sales Data Cleaning

This project focuses on cleaning and preparing a real-world vehicle sales dataset using Python (Pandas & NumPy). The objective was to transform raw, unstructured data into a clean and analysis-ready format.

---

## 📁 Dataset Source

The raw dataset used in this project is available on Kaggle:

https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data

Note: The raw dataset is not included in this repository due to GitHub file size limitations.

---

## 🧹 Data Cleaning Steps Performed

The following preprocessing steps were applied:

- Initial dataset inspection (`head()`, `info()`, `describe()`)
- Missing value analysis using `isnull()`
- Missing values handled using mean imputation (for numerical features)
- Duplicate record detection
- Data type validation
- Column name standardization (lowercase formatting)
- Exported final cleaned dataset

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 📂 Project Structure

- `notebook/` → Data cleaning notebook  
- `cleaned_data/` → Final cleaned dataset  
