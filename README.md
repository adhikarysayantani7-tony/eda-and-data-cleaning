# Exploratory Data Analysis (EDA) & Data Cleaning

## Project Overview
This repository contains an end-to-end data cleaning and exploratory data analysis (EDA) pipeline applied to the Titanic passenger dataset. The workflow addresses missing values, treats extreme outliers using the Interquartile Range (IQR) method, and explores feature relationships with Seaborn visualizations.

## Repository Architecture
- README.md
- .gitignore
- data/raw_dataset.csv
- data/cleaned_dataset.csv
- notebooks/eda_and_cleaning.ipynb
- docs/summary_report.pdf

## Mini-Tasks Accomplished
1. Data Profiling & Missing Value Treatment (Mini-Task 1):
   - Assessed null percentages across all attributes.
   - Removed duplicate records.
   - Imputed numerical Age using median imputation and categorical Embarked using mode imputation.
2. Outlier Detection & Treatment (Mini-Task 2):
   - Visualized numerical distributions using Seaborn box plots.
   - Detected extreme ticket fares and applied IQR threshold capping (Q3 + 1.5 * IQR).
3. Correlation Analysis (Mini-Task 3):
   - Generated a Seaborn correlation heatmap across numerical variables.
   - Identified significant patterns relating passenger class, ticket fare, and survival probability.

## How to Run
- Review the analysis directly on GitHub inside `notebooks/eda_and_cleaning.ipynb`.
- Read the complete executive overview and methodology in `docs/summary_report.pdf`.
