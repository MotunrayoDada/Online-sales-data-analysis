# Online-sales-data-analysis

### Project Overview

This project explores an online sales dataset to understand sales performance, transaction patterns, and differences across product categories and sales channels. Completed as part of a Python capstone course, the project applies data cleaning, exploratory data analysis, visualization, and statistical testing to a real-world business dataset.

The analysis was carried out using **Python in Google Colab**.

### Objectives

- Examine sales performance across product categories, sales channels, and countries.
- Identify patterns and relationships among sales, quantity, prices, and discounts.
- Apply statistical tests to evaluate differences and associations in the data.
- Assess whether a random sample produces results comparable to the full dataset.

### Dataset

**Source:** [Online Sales Dataset – Kaggle (Yusuf Delikkaya)](https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset)

The original dataset contains **49,782 transactions and 17 variables**, covering product information, transaction values, payment methods, sales channels, and shipping details.

Following data cleaning, **47,293 observations** were retained for analysis.

### Methods and Analysis

The project involved:

- **Data Cleaning:** Handling missing values, correcting data types, checking duplicates, and examining outliers.
- **Exploratory Analysis:** Investigating sales distributions, product-category performance, sales channels, and transaction trends.
- **Visualization:** Using histograms, bar charts, scatter plots, box plots, and correlation heatmaps.
- **Statistical Testing:** Applying an independent two-sample t-test, one-way ANOVA, and chi-square test of independence.
- **Data Transformation and Sampling:** Using pivot tables, data subsetting, and a 20% random sample to compare findings.

### Key Findings

- Total sales amounted to approximately **44.63 million**, with average sales of **943.77 per transaction**.
- Furniture generated the highest total sales among the product categories, at approximately **9.03 million**.
- Statistical tests were used to examine differences in average sales across channels and categories, as well as the association between sales channel and return status.

Detailed analysis, visualizations, and statistical results are provided in the notebook.

### Tools and Libraries

**Python | Google Colab | Pandas | NumPy | Matplotlib | Seaborn | SciPy**

### Repository Contents

- **Online Sales Analysis (`.ipynb`):** Contains the Python code, explanations, visualizations, statistical tests, and sampling analysis.

### How to Run the Project

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset).
2. Open the `.ipynb` notebook from this repository in [Google Colab](https://colab.research.google.com/).
3. Upload the CSV dataset to your Colab session using the **Files → Upload** option.
4. Ensure the CSV filename matches the one specified in the notebook (`Online Sales Data-Capstone.csv`), then select **Runtime → Run all**.

### Project Outcome

This project strengthened my practical skills in Python programming, data management, statistical analysis, and interpreting quantitative findings from transaction-level data.
