# Alt_mobility_assignment

# 🧠 Cohort Analysis with Python & Power BI

This project performs **Cohort Analysis** on user behavior data using **Python (Google Colab)** for preprocessing and **Power BI** for data visualization. The goal is to analyze user retention trends across different cohorts over time.

---

## 📂 Dataset

The dataset is a 65x65 matrix:
- **Rows** represent different cohort groups (based on the user's first activity month).
- **Columns** represent subsequent months from the user's start date (i.e., `cohort_index`).
- Each cell contains a **retention metric** (e.g., count or rate).

---

## ⚙️ Steps & Tools Used

### 🔸 1. Python Preprocessing (Google Colab)
- Loaded the `.csv` file
- Cleaned and transformed the matrix format
- Reshaped the data using `melt()` to create:
  - `cohort_month`
  - `cohort_index`
  - `retention_value`
- Exported cleaned file as `.csv` for Power BI

> 📁 File: `cohort_data_transformed.csv`

---

### 🔸 2. Power BI Visualization

#### Power Query
- Loaded the transformed CSV
- Used **Unpivot Columns** to reshape data (if needed)
- Ensured proper data types (e.g., Date, Number)

#### Power BI Visual
- Created a **Matrix visual**:
  - **Rows:** `cohort_month`
  - **Columns:** `cohort_index`
  - **Values:** `retention_value`
- Added **Conditional Formatting** to highlight retention trends with color scales

---

## 📊 Key Insights

- View how different cohorts retain users over time
- Identify strong and weak retention months
- Compare cohort behaviors using a dynamic heatmap

---

## 🧰 Tech Stack

- Python (pandas, numpy)
- Google Colab
- Power BI (Power Query, Matrix visuals, Conditional Formatting)

---

## 📎 Files Included

- `cohort_analysis_colab.ipynb` – Colab notebook for preprocessing
- `cohort_data_transformed.csv` – Cleaned CSV for Power BI
- `powerbi_report.pbix` – Power BI dashboard file 
- `README.md` – Documentation

---


## 📧 Contact

Created by Yash namdev  
Feel free to reach out for collaboration or questions!  
📩 Email: namdevy799@gmail.com 



