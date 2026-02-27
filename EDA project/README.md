# 📊 Netflix Exploratory Data Analysis (EDA) Project

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Titles dataset to understand content distribution, growth trends, and platform strategy.

The objective of this project is to:
- Understand the structure and quality of the dataset
- Clean and preprocess raw data
- Perform univariate and bivariate analysis
- Conduct statistical testing
- Perform time-based analysis
- Engineer new features
- Generate meaningful business insights

---

## 📂 Dataset Description

The dataset contains information about Netflix Movies and TV Shows.

Each row represents one Netflix content item.

### Key Columns:
- **show_id** – Unique content identifier
- **type** – Movie or TV Show
- **title** – Content name
- **director** – Director name
- **cast** – Actors
- **country** – Country of production
- **date_added** – Date added to Netflix
- **release_year** – Original release year
- **rating** – Content maturity rating
- **duration** – Duration (minutes or seasons)
- **listed_in** – Genre
- **description** – Short summary

---

## 🏗️ Project Structure
eda-project/
│
├── data/
│ ├── raw/
│ ├── interim/
│ └── processed/
│
├── notebooks/
│ ├── 01_data_overview.ipynb
│ ├── 02_cleaning_preprocessing.ipynb
│ ├── 03_univariate_bivariate_eda.ipynb
│ └── 04_stats_time_features_final_insights.ipynb
│
│
├── README.md
└── requirements.txt

---

## 🧹 Data Cleaning

- Handled missing values in categorical columns
- Converted `date_added` to datetime format
- Removed duplicate records
- Standardized categorical variables
- Checked outliers using boxplots
- Saved cleaned dataset for further analysis

---

## 📊 Exploratory Data Analysis

### Univariate Analysis
- Distribution of Movies vs TV Shows
- Release year distribution
- Rating distribution
- Duration analysis

### Bivariate Analysis
- Content type vs release year
- Rating vs content type
- Year added vs content type
- Correlation heatmap of numeric features

---

## 📈 Statistical Tests Performed

- **T-test** – Compared release years between Movies and TV Shows
- **ANOVA** – Compared release years across rating categories
- **Chi-square test** – Analyzed relationship between type and rating

These tests validated observed patterns statistically.

---

## ⏳ Time-Based Analysis

Extracted:
- Year added
- Month added
- Day added

This helped analyze Netflix growth trends over time.

---

## 🛠️ Feature Engineering

Created new features:

- `year_added`
- `month_added`
- `day_added`
- `content_age`
- `is_recent`
- `duration_num`

These features enabled deeper analysis of content trends.

---

## 🔍 Key Insights

- Netflix content additions increased significantly after 2016.
- Movies dominate the platform compared to TV Shows.
- Netflix focuses mainly on recent content.
- Mature-rated content (TV-MA, TV-14) is highly common.
- Statistical tests confirmed significant differences between content categories.

---

## 🧰 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Git & GitHub

---

## ▶️ How to Run the Project

1. Clone this repository
2. Install required libraries:

pip install -r requirements.txt

3. Open notebooks in order and run all cells.

---

## 📁 Final Processed Dataset

The final cleaned dataset is available at:


data/processed/final_cleaned_day4.csv


---

## 📌 Conclusion

This project demonstrates a complete EDA workflow including data cleaning, visualization, statistical validation, and feature engineering. It provides meaningful insights into Netflix’s content growth and distribution strategy.
