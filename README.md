# 🫀 Heart Disease Data Analysis
## 📌 Overview
This notebook presents a comprehensive exploratory and predictive analysis of heart disease data using Python and key machine learning libraries. The goal is to uncover patterns in cardiovascular health indicators and build models that can classify the presence of heart disease based on clinical features.

## 📂 Dataset
Source: heart.csv

Records: 303 patients

Features: 14 clinical attributes including age, sex, chest pain type, cholesterol levels, resting blood pressure, and more.

Target: output (binary classification: 1 = presence of heart disease, 0 = absence)

## 🧪 Methodology
1. Data Preprocessing
Renamed columns for clarity (e.g., cp → Chest Pain, trtbps → Resting Blood Pressure)

Checked data types and null values

Basic statistical summaries and distribution checks

2. Exploratory Data Analysis (EDA)
Visualized distributions using seaborn and matplotlib

Assessed skewness and kurtosis

Used scatter matrices to explore feature relationships

3. Modeling
Applied and compared multiple classification algorithms:

Logistic Regression


K-Nearest Neighbors

Linear Discriminant Analysis


4. Evaluation
Accuracy Score



## 📈 Results
The notebook benchmarks several models to identify the most effective classifier for predicting heart disease. Performance metrics are used to guide model selection and highlight trade-offs between precision and recall.

🛠️ Technologies Used
Python (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn)

Databricks Notebook environment

🤝 Contribution
This notebook is part of a broader effort to explore AI applications in healthcare and social impact. Contributions, suggestions, and forks are welcome.

📜 License
This project is open-source under the Apache 2.0 License
