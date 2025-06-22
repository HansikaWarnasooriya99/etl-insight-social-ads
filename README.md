# 📊 ETL & Insight Challenge – Social Advertisement Dataset

## 📝 Project Overview

This project demonstrates a complete ETL (Extract → Transform → Load) pipeline and data insight analysis on the Social Advertisement dataset. It was built as part of a data internship challenge to evaluate ETL and analytical skills using Python.

## ⚙️ Technologies Used

- Python (Pandas, NumPy)
- Data Visualization: Seaborn, Matplotlib
- SQLite (for optional data loading)
- Google Colab
- GitHub

## 🔄 ETL Process

### ✅ Extract
- Loaded raw data from a CSV file.

### ✅ Transform
- Cleaned column names.
- Converted target variable `purchased` to categorical.
- Created meaningful age groups (e.g., 18-24, 25-34).
- Removed redundancy and standardized data.

### ✅ Load
- Exported cleaned data to:
  - CSV: `cleaned_social_ads.csv`
  - SQLite DB: `social_ads.db` (bonus)

## 📊 Key Insights

- Users aged **25–34** and **35–44** are more likely to purchase.
- There's **no strong correlation** between salary and purchase.
- Visual clusters suggest potential for **targeted ad campaigns**.

## 📂 Files

- `etl_insight_social_ads.ipynb`: Full Colab notebook
- `cleaned_social_ads.csv`: Cleaned and transformed dataset
- `social_ads.db`: SQLite version of the data (bonus)
- `README.md`: Project description and explanation

## 📎 Dataset Source

This dataset is originally from Kaggle:
> *https://www.kaggle.com/datasets/sakshisatre/social-advertisement-dataset?resource=download*

## ✨ Author
- Hansika Warnasooriya
- LinkedIn : *https://www.linkedin.com/in/hansika-warnasooriya*
- Portfolio: *https://hansikawarnasooriy.wixsite.com/portfolio*

