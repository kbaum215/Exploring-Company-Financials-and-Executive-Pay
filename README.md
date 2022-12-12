# Analyzing Company Financials to Classify Executive Titles
#### Kevin W.S. Baum and Stephen F. Reagin

This is a project satisfying the requirements of the Fall 2022 cohort of ADS502, Applied Data mining.

## Motivation

The motivation of this project is to investigate the use of machine learning techniques when applied to datasets of executive compensation. As an initial goal we ask, **can machines tell the difference between CEO and CFO roles based on their pay components and company financial performance over a 10-year period?**

We created a unique dataset using API calls from sec-api.io to gather executive pay components and combined these with Excel-based financial workbooks from stockrow.com. After EDA and data preprocessing stages, we ran a series of binary classification models to predict CEOs vs CFOs, and evaluated these predictions via confusion matrix metrics such as accuracy.

## Navigation

The repository is organized in several subdirectories:

### [Analysis](https://github.com/kbaum215/ADS502_Group_Project/tree/main/Analysis)

This directory contains iterative attempts for analyzing the data and experimental trials. 

For final classification model results, please see the [classification_models.ipynb Jupyter notebook](https://github.com/kbaum215/ADS502_Group_Project/blob/main/Analysis/classification_models.ipynb)

### [datasets](https://github.com/kbaum215/ADS502_Group_Project/tree/main/datasets)

This directory contains both raw and processed datasets, used for exploratory data analysis and modeling, respectively.

### [EDA](https://github.com/kbaum215/ADS502_Group_Project/tree/main/EDA)

This directory contains Jupyter notebooks for analyzing the raw datasets as well as preprocessing for eventual modeling. See [EDA_CEO_changes.ipynb](https://github.com/kbaum215/ADS502_Group_Project/blob/main/EDA/EDA_CEO_changes.ipynb) to review the primary working notebook.

### [images](https://github.com/kbaum215/ADS502_Group_Project/tree/main/images)

This directory contains notable images of data visualizations relevant to EDA and model evaluation.
