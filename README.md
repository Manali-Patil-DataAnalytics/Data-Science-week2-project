# Week 2 Data Science Internship Project

# Project Overview

This project was completed as part of the Week 2 Data Science Internship assignment at WeIntern Pvt Ltd. It covers data cleaning, Exploratory Data Analysis (EDA), and sales prediction using machine learning.

# Objectives

- Clean the retail sales dataset and handle missing values.
- Explore the data using statistics, charts, and business insights.
- Build and evaluate machine learning models to predict daily sales.
- Document the results and limitations of the analysis.

# Dataset

The project uses a retail store sales dataset downloaded from Kaggle.

- Raw dataset: `dataset/raw/retail_store_sales.csv`
- Cleaned dataset: `dataset/cleaned/retail_sales_cleaned.csv`

The original dataset is kept separately from the cleaned dataset.

# Tools and Libraries

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

# Tasks Completed

# Task 1: Data Cleaning

The raw dataset was inspected and cleaned. Missing values, duplicates, data types, and potential outliers were checked. The cleaned dataset was saved separately.

# Task 2: Exploratory Data Analysis

Descriptive statistics, histograms, KDE plots, a correlation heatmap, box plots, scatter plots, grouped analysis, and sales trends were examined. Key findings and recommendations were documented in the notebook.

# Task 3: Sales Prediction

Daily sales were calculated from transaction records. Date-based features, previous-day sales, and the previous seven-day average were created.

Linear Regression, Random Forest Regression, and a tuned Random Forest model were trained and evaluated using MAE, RMSE, and R². Actual-versus-predicted sales and feature importance graphs were created.

Linear Regression achieved the lowest MAE among the three models. However, all three models had negative R² scores, indicating that further improvement is needed.

# Project Structure

```text
week 2/
├── dataset/
│   ├── raw/
│   │   └── retail_store_sales.csv
│   └── cleaned/
│       └── retail_sales_cleaned.csv
├── notebook/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_sales_prediction.ipynb
├── outputs/
│   └── eda_graphs/
├── reports/
│   └── 02_eda_report.pdf
└── README.md
```

# How to Run the Project

1. Open the project folder in VS Code.
2. Make sure Python and the Jupyter extension are installed.
3. Install the required libraries using the terminal:

   `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`

4. Open the notebooks in the `notebook` folder.
5. Run the notebooks in this order:
   - `01_data_cleaning.ipynb`
   - `02_eda.ipynb`
   - `03_sales_prediction.ipynb`
6. Ensure the dataset paths are correct before running the cells.

# Limitations

The results depend on the quality of the dataset and the features used. The sales prediction models did not achieve strong predictive performance, so additional features and forecasting methods should be explored.

# Conclusion

This project provided practical experience in data cleaning, exploratory analysis, data visualization, feature engineering, machine learning, and model evaluation.
