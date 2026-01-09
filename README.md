Statistical Analysis & Exploratory Data Analysis – Customer Churn

#Objective
This project focuses on exploratory data analysis (EDA) and statistical exploration of customer churn data.
The goal is to understand data structure, quality, variable distributions, and relationships that may influence customer retention, providing a solid analytical foundation for further modeling or business decision-making.

#Dataset
The dataset contains customer-level information including:
- customer characteristics
- usage-related numerical variables
- categorical features
- a binary churn indicator
(Column names and values have been anonymized for confidentiality and educational purposes)

#Analysis Workflow
The analysis follows a structured and reproducible pipeline:
1. Data Loading & Inspection: Dataset structure and variable types; Initial statistical summary and Data consistency checks

2. Data Cleaning: Removal of irrelevant or identifier columns; Duplicate detection and handling; Missing value analysis with feature-specific strategies and Type conversions and validation

3. Outlier Handling
Outliers identified using the Interquartile Range (IQR) method; Extreme values flagged instead of removed to avoid information loss and Outlier flags preserved for downstream analysis

4. Univariate Analysis
Distribution analysis of numerical features; Frequency analysis of categorical variables and Churn class balance assessment

5. Bivariate Analysis
Pairwise relationships between numerical features; Scatterplots highlighting churn patterns and Correlation analysis to identify related variables and potential redundancy

6. Analytical Insights
Identification of features potentially associated with churn; Detection of structural patterns useful for feature selection and Data-driven insights to guide subsequent analysis steps

#Tools & Technologies
- Python: pandas, numpy, matplotlib, seaborn
- Excel: preliminary data inspection, data validation and consistency checks

#Project Scope
This repository is intended to demonstrate:
- structured exploratory analysis
- statistical reasoning
- data cleaning best practices
- clear analytical communication

It is not focused on predictive modeling, but on building a robust analytical foundation.

## Related Projects

This exploratory analysis serves as the analytical foundation for subsequent projects:

- **Customer Segmentation (K-Means)**  
  https://github.com/tuo-username/customer-segmentation-kmeans

- **KPI & Business Analysis (Telco–Utility Partnership)**  
  https://github.com/tuo-username/kpi-analysis-telco-utility
