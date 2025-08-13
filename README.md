Insurance Data Analysis & Prediction
This project analyzes an insurance dataset to explore patterns in medical costs and builds a predictive model to estimate charges based on demographic and lifestyle factors. It includes Exploratory Data Analysis (EDA), data cleaning, and regression modeling with accuracy evaluation.

📌 Project Overview
The notebook:

Loads and explores the dataset.

Performs statistical summaries and visualizations.

Cleans the data by removing duplicates.

Builds a machine learning model to predict medical charges.

Calculates model accuracy to evaluate performance.

📂 Files
insurance.ipynb — Jupyter Notebook with EDA, data cleaning, model training, and evaluation.

insurance.csv — Dataset used for analysis (should be placed in the same directory).

README.md — Documentation.

📊 Dataset
Source: Kaggle - Medical Cost Personal Dataset
Columns:

age — Age of the insured

sex — Gender

bmi — Body Mass Index

children — Number of dependents covered

smoker — Smoking status

region — Residential region

charges — Medical insurance cost

Perform EDA and visualize patterns.

Clean and prepare the dataset.

Train a regression model.

Evaluate model accuracy.

📈 Analysis Performed
EDA:

Histograms with KDE for numerical variables.

Countplots for categorical variables.

Boxplots to detect outliers.

Correlation heatmap.

Data Cleaning:

Duplicate removal.

Modeling:

Encoded categorical features.

Trained regression model (e.g., Linear Regression).

Calculated accuracy score to measure prediction performance.

📊 Example Model Performance
Accuracy: 79% 

Evaluation Metric: R² score (regression) or classification accuracy (if applicable).
