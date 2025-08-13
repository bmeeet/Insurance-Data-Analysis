# Insurance-Data-Analysis
This project performs Exploratory Data Analysis (EDA) on an Insurance dataset to identify patterns and trends in medical costs based on demographic and lifestyle factors.

📌 Project Overview
The analysis:

Loads and inspects the dataset.

Summarizes key statistics.

Checks for missing values.

Visualizes numerical variables like age, BMI, children, and charges.

Prepares for potential data cleaning, feature engineering, and predictive modeling (placeholders included in the notebook).

📂 Files in This Repository
insurance.ipynb — Jupyter Notebook with EDA and analysis.

insurance.csv — Dataset file (must be present in the same folder).

README.md — Project documentation.

📊 Dataset
Name: Insurance Dataset

Source: Kaggle - Medical Cost Personal Dataset

Columns:

age — Age of the primary beneficiary

sex — Gender (male, female)

bmi — Body mass index

children — Number of children covered by health insurance

smoker — Smoking status (yes, no)

region — Residential area in the US

charges — Individual medical costs billed by health insurance

Load and inspect the dataset.

Generate statistical summaries.

Visualize distributions of numerical features.

📈 Analysis Performed
Basic EDA: .shape(), .head(), .info(), .describe()

Missing value check: .isnull().sum()

Visualization: Histograms with Kernel Density Estimation (KDE) for numerical columns.

Preparation: Notebook contains placeholders for:

Data Cleaning & Preprocessing

Feature Engineering & Extraction

Model Testing
