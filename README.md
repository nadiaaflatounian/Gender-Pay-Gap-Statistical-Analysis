
# Analyzing Gender Pay Gap Data

## Overview

This Jupyter notebook, `Gender Pay Gap Analysis.ipynb`, provides a comprehensive analysis of a dataset related to gender pay gaps. The notebook includes data preprocessing, exploratory data analysis (EDA), and statistical testing to understand the relationships between various features in the dataset.

## Contents

The notebook covers the following sections:

1. **Introduction**:
   - Imports and initial setup for the analysis.

2. **Data Loading and Inspection**:
   - Loading the dataset into a Pandas DataFrame.
   - Inspecting the dataset for an initial understanding of its structure and content.

3. **Data Preprocessing**:
   - Cleaning the data, handling missing values, and preparing the data for analysis.

4. **Exploratory Data Analysis (EDA)**:
   - Descriptive statistics for the dataset.
   - Visualizing the distribution of key variables, including histograms and plots for `BasePay` and `Bonus`.
   - Frequency histograms for categorical variables such as `JobTitle`, `Seniority`, `Age`, `PerfEval`, and `Education`.

5. **Statistical Analysis**:
   - Correlation analysis to understand the relationships between variables.
   - Pearson and Spearman correlation tests for `BasePay` and `Bonus`, and `Age` and `Bonus`.
   - Interpretation of the correlation results.

6. **Results and Discussion**:
   - Detailed analysis of the correlation coefficients.
   - Discussion of findings and their implications.

7. **Conclusion**:
   - Summary of the key points and results of the analysis.
   - Recommendations for further analysis and potential improvements.

## Requirements

Before running the notebook, ensure you have the following libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `researchpy`
