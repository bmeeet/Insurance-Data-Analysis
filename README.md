#Insurance Data Analysis
This project analyzes an insurance dataset to explore patterns and relationships in medical costs based on demographic and lifestyle factors. It includes Exploratory Data Analysis (EDA), data cleaning, and preparation steps for future predictive modeling.

📌 Project Overview
The notebook:

Loads and inspects the dataset.

Performs statistical summaries and visualizations.

Cleans data by removing duplicates.

Prepares the dataset for future feature engineering and modeling.

📂 Files
insurance.ipynb — Jupyter Notebook with full analysis.

insurance.csv — Dataset used in the analysis (should be placed in the same directory).

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

⚙️ Installation
bash
Copy
Edit
git clone https://github.com/yourusername/insurance-analysis.git
cd insurance-analysis
pip install numpy pandas seaborn matplotlib
🚀 Usage
bash
Copy
Edit
jupyter notebook
Open insurance.ipynb and run cells in sequence.

📈 Analysis Performed
EDA:

Histograms with KDE for numerical variables.

Countplots for categorical variables.

Boxplots to detect outliers.

Correlation heatmap.

Data Cleaning:

Duplicate removal.

Preparation:

Dataset ready for feature engineering and modeling.
