# Walmart Sales Analysis: Central Limit Theorem & Confidence Intervals

**Author: Sudhansu Ranjan Singh**

## 📌 Project Overview

This project analyzes Walmart customer purchase data using Python, Pandas, NumPy, Matplotlib, and Seaborn.

The analysis covers data cleaning, exploratory data analysis, the Central Limit Theorem (CLT), sampling distributions, and confidence intervals to understand customer purchase behavior across different demographic groups.

## 🎯 Business Questions

- How does customer purchase behavior vary across different demographic groups?
- Is there a difference in average purchase amount between male and female customers?
- What can confidence intervals tell us about population-level purchase behavior?
- Is there a significant difference in average purchase amount between married and unmarried customers?
- How can statistical analysis support better business decisions?

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## 🔍 Analysis Performed

### 1. Data Cleaning & Exploration

- Loaded and explored 550,068 Walmart transactions.
- Examined data types and dataset structure.
- Checked for missing values.
- Performed exploratory data analysis on customer purchase behavior.

### 2. Outlier Treatment

Used the Interquartile Range (IQR) method to identify purchase amount outliers.

- Q1: 5,823
- Q3: 12,054
- IQR: 6,231
- Identified 2,677 outlier transactions.
- Outliers represented approximately 0.49% of the dataset.
- Removed the outliers for further analysis.

### 3. Central Limit Theorem

Applied the Central Limit Theorem to understand the behavior of sample means and their sampling distributions.

### 4. Confidence Interval Analysis

Calculated confidence intervals to estimate the range in which the true population mean purchase amount is likely to fall.

A 99% confidence interval was used for the comparison of customer groups.

### 5. Customer Demographic Analysis

Compared purchase behavior across demographic groups, including:

- Gender
- Age
- Marital Status
- City Category

## 💡 Key Insights

- The analysis identified differences in average purchase amounts between male and female customers.
- The Central Limit Theorem demonstrated how sample means behave across repeated samples.
- For marital status, the 99% confidence intervals were:
  - **Married customers:** 9,160.05 to 9,205.70
  - **Unmarried customers:** 9,188.40 to 9,234.15
- The confidence intervals for married and unmarried customers overlap, so the analysis does not provide sufficient evidence from the confidence intervals alone to conclude that their mean purchase amounts are significantly different.

## 🏁 Conclusion

The Walmart customer purchase analysis demonstrates how statistical inference can be applied to a large retail dataset to understand customer purchasing behavior.

The project strengthened practical understanding of exploratory data analysis, outlier treatment, sampling distributions, the Central Limit Theorem, and confidence intervals using Python.

The analysis can support customer segmentation and data-driven understanding of purchasing behavior.

## 📄 Project Report

[📥 View Walmart Project Report](Walmart_Analysis.pdf)

## 👨‍💻 Author

**Sudhansu Ranjan Singh**

Data Analyst | BI Analyst | Product & Business Analyst
