# Talent Academy Data Science Case Study
**Prepared by:** Tuana Bayazıt 

**Email:** byztuana@gmail.com

---

## 1. About the Project

This project was conducted on a dataset containing physical medicine and rehabilitation data.

The dataset contains **2235 observations and 13 features**. The goal is to perform **EDA (Exploratory Data Analysis)** and data preprocessing steps to prepare the data for modeling.

Target variable: **TedaviSuresi**

Project scope:
- Dataset structure and missing/data type issues were analyzed.
- Relationships and distributions were examined through visualization.
- Categorical and numerical data were processed and standardized appropriately.
- As a result, a dataset ready for modeling was created.

---

## 2. File Descriptions

- **Talent_Academy_Case_DT_2025.xlsx**: Original dataset (2235 observations, 13 features).
- **eda.ipynb** → Dataset exploration, statistical summaries, and visualizations (histograms, scatter plots, heatmaps)
- **preprocessing.ipynb** → Data cleaning and preprocessing steps:
  - Filling in missing values
  - Coding categorical variables
  - Processing of comma-separated values ​​(presence flag for the top 5 items)
  - Standardization of numerical features
  - Preparation of training and test sets
- **preprocessed_case_study.csv** → Dataset ready for modeling after preprocessing
- **preprocessor.joblib** → Preprocessing pipeline, reusable and ready for modeling
- **README.md** → Project description and instructions

---

## 3. Instructions for Running the Project

1. Clone the GitHub repo to your computer or Colab.
2. Since all the files are in the same folder, you can read the Excel file directly as follows:

```python
import pandas as pd
df = pd.read_excel("Talent_Academy_Case_DT_2025.xlsx")
