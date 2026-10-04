# Indian Urban Waste Management — Data Science Mini Project

## 📌 Project Overview

This mini-project applies the complete **Data Science and Machine Learning workflow** to the real-world problem of **Indian urban waste management**.

The project analyzes waste-management and sustainability-related data for Indian cities and builds machine-learning models to predict:

* **Waste Management Performance Level** — Classification
* **Sustainability Index** — Regression

The complete workflow includes **data collection, data understanding, preprocessing, exploratory data analysis (EDA), statistical analysis, machine learning, model evaluation, interpretation, and deployment**.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand and analyze Indian urban waste-management data.
* Perform data cleaning and preprocessing.
* Explore important patterns and relationships in the dataset.
* Perform statistical analysis and hypothesis testing.
* Build classification models for waste-management performance.
* Build regression models for sustainability prediction.
* Evaluate and compare machine-learning models.
* Interpret the results and identify useful insights.
* Develop a simple Streamlit application for prediction.

---

## 📊 Dataset

**Dataset:** Indian Urban Waste Management Dataset

| Property       | Details                  |
| -------------- | ------------------------ |
| Records        | 25,203                   |
| Columns        | 42                       |
| Cities         | 130                      |
| Years          | 2015–2026                |
| Missing Values | None in supplied dataset |

### Target Variables

**Classification Target**

`Waste_Management_Performance_Level`

* Low
* Medium
* High

**Regression Target**

`Sustainability_Index`

**Secondary Category**

`Sustainability_Category`

* Poor
* Average
* Good
* Excellent

`Record_ID` is treated as an identifier and is not used as a predictive feature.

---

## 🔄 Data Science Workflow

Data Collection
      ↓
Data Understanding
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Statistical Analysis
      ↓
Machine Learning
      ↓
Model Evaluation
      ↓
Interpretation
      ↓
Streamlit Deployment
      ↓
Final Presentation
```

---

## 🤖 Machine Learning Models

### Classification

Target:

`Waste_Management_Performance_Level`

Models:

1. Logistic Regression
2. Decision Tree Classifier

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### Regression

Target:

`Sustainability_Index`

Models:

1. Linear Regression
2. Random Forest Regressor

Evaluation metrics:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

## 📈 Exploratory Data Analysis

The project includes:

* Summary statistics
* Mean, median and standard deviation
* Categorical variable analysis
* Target distribution analysis
* Histograms
* Density plots
* Box plots
* Bar charts
* Line charts
* Scatter plots
* Correlation analysis
* Correlation heatmap

---

## 📐 Statistical Analysis

A meaningful hypothesis test related to the waste-management dataset will be performed.

The statistical analysis will be used to examine relationships or differences between relevant variables and interpret the results in the context of urban waste management.

---

## 🧹 Data Preprocessing

The preprocessing stage includes:

* Missing-value checking
* Duplicate checking
* Outlier analysis using the Z-score method
* Categorical variable encoding
* Feature selection
* Removal of `Record_ID`
* Prevention of target leakage
* Train/test splitting

The final feature list and preprocessing rules will be agreed upon by both project members before final model training.

---

## 📁 Project Structure

Waste-Management-ML/
│
├── data/
│   └── data_set.csv
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Preprocessing.ipynb
│   ├── 03_EDA_Statistics.ipynb
│   ├── 04_Regression_Classification.ipynb
│   └── 05_Final_Integration.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── eda.py
│   ├── statistics.py
│   ├── classification.py
│   └── regression.py
│
├── models/
│   ├── logistic_regression.pkl
│   ├── decision_tree.pkl
│   ├── linear_regression.pkl
│   └── random_forest.pkl
│
├── results/
│   ├── figures/
│   │   ├── histograms/
│   │   ├── boxplots/
│   │   ├── barplots/
│   │   ├── lineplots/
│   │   ├── scatterplots/
│   │   └── heatmaps/
│   │
│   ├── classification_results.csv
│   ├── regression_results.csv
│   └── statistical_test_results.txt
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
