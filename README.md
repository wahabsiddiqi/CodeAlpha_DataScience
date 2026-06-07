# CodeAlpha Data Science Internship Portfolio

Welcome to my **CodeAlpha Data Science Internship** repository! This repository contains three comprehensive data science projects that showcase end-to-end machine learning workflows, rigorous exploratory data analysis (EDA), and insightful data visualizations.

All projects have been executed with 100% data integrity, zero unhandled missing values, and complete performance validations.

---

## 📂 Repository Structure

```text
CodeAlpha_DataScience/
│
├── 01_Iris_Classification/
│   ├── iris_analysis.ipynb      # Jupyter Notebook containing Stacking & Ensemble models
│   └── Iris.csv                # Dataset file
│
├── 02_Unemployment_Analysis/
│   ├── unemployment_study.ipynb # Jupyter Notebook focusing on COVID-19 impact analysis
│   └── Unemployment_Rate.csv    # Dataset file
│
└── 03_Car_Price_Analysis/
    ├── car_analysis.ipynb       # 20-cell detailed Exploratory Data Analysis (EDA)
    └── car_data.csv             # 100% Clean CarDekho dataset (Zero Null Values)
    🚀 Project 1: Iris Flowers Classification (Ensemble & Stacking)





```
📌 Project Overview
A machine learning project focused on predicting the species of Iris flowers (Iris-setosa, Iris-versicolor, Iris-virginica) based on morphological measurements (sepal length, sepal width, petal length, and petal width). Instead of basic classification, this project implements advanced meta-learning architecture to achieve maximum generalization.

🛠️ Key Technical Highlights
Data Preprocessing: Implemented feature separation, label encoding via LabelEncoder, and stratified splitting to ensure perfectly balanced class distributions across train and test partitions.

Advanced Stacking Architecture:

Base Learners: Built an ensemble of heterogeneous classifiers including DecisionTreeClassifier, SVC (Support Vector Classifier with Radial Basis Function kernel), and LogisticRegression.

Meta-Learner: Combined individual predictions using a secondary LogisticRegression meta-classifier orchestrated via StackingClassifier with 5-Fold Cross-Validation (cv=5).

Ensemble Benchmarking: Compared performance against high-performing boosting frameworks including AdaBoostClassifier, GradientBoostingClassifier, and XGBClassifier.

Performance Evaluation: Achieved an absolute 1.0 (100%) accuracy score, verified across all evaluation confusion metrics and classification reports without over-fitting.

📈 Project 2: Unemployment Analysis in India (COVID-19 Impact Study)
📌 Project Overview
A quantitative data analytics project evaluating the sharp macroeconomic shifts in India's labor market during the year 2020. The project focuses heavily on capturing the structural impact of strict COVID-19 pandemic lockdowns on regional employment metrics.

🛠️ Key Technical Highlights
Temporal Analysis: Processed historical monthly series of regional estimated unemployment rates, employed workforce counts, and labor participation rates.

Exploratory Data Analysis (EDA): Cleaned, filtered, and parsed date features to isolate pre-lockdown data versus post-lockdown spikes.

Advanced Visualizations:

Designed interactive and high-density statistical charts utilizing Matplotlib and Seaborn.

Highlighted massive unemployment spikes during the March-May 2020 peak lockdown periods.

Compared rural vs. urban labor force dynamics, showcasing the stark contrast in economic resilience across different Indian states.

🚗 Project 3: Used Car Price Exploratory Data Analysis (EDA)
📌 Project Overview
A meticulous, deep-dive Exploratory Data Analysis (EDA) project conducted over a structural sequence of 20 processing cells. The objective is to decipher the underlying economic drivers that dictate the market resale value (Selling_Price) of vehicles based on real historical automotive marketplace data.

🛠️ Key Technical Highlights
Data Integrity & Zero-Null Architecture: Inspected structural dimensionality using .shape, .info(), and .describe(). Verified 0 missing values using .isnull().sum() to guarantee absolute clean analytical workflows.

Feature Engineering Alignment: Handled complex structural variations across column schemas (e.g., dynamically adjusting and mapping variables such as Driven_kms and Selling_type).

20-Cell Granular Analysis:

Categorical Distributions: Analyzed fuel categories (Fuel_Type) and transmission types (Transmission) using descriptive pie-charts and count-plots.

Price Depreciation Metrics: Plotted cross-feature scatter-plots mapping Present_Price against Selling_Price to evaluate vehicle depreciation thresholds.

Usage Correlation: Investigated the negative correlation between higher accumulated mileage (Driven_kms) and market price decline.

Multivariate Correlation Matrix: Computed and rendered a clear Seaborn Heatmap over all filtered continuous numerical values (int64 and float64), providing clear structural insights into pricing correlations at a single glance.

🔧 Installation & Execution
To explore the notebooks locally on your machine, follow these setup steps:

Clone the Repository:

Bash
git clone [https://github.com/AbdulWahab/CodeAlpha_DataScience.git](https://github.com/AbdulWahab/CodeAlpha_DataScience.git)
cd CodeAlpha_DataScience
Set Up the Environment:
Make sure you have Anaconda or Python installed. Install all necessary data science frameworks via terminal:

Bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
Launch Jupyter:
Navigate into any specific project directory and fire up the notebook interface:

Bash
jupyter notebook
👤 Intern Information
Name: Abdul Wahab

Role: Data Science Intern

Company: CodeAlpha

Portfolio Focus: Machine Learning, Predictive Modeling, and Exploratory Data Analysis (EDA).
