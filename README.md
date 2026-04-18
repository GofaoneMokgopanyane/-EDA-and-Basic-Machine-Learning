# 🌍 EDA and Basic Machine Learning on Seismic Data

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** and building basic machine learning models on a public seismic dataset. The goal is to understand patterns in seismic activity and evaluate how well we can predict or classify events using simple models.

Seismic data is critical in understanding earthquakes, underground activity, and potential hazards. Through this project, we aim to uncover meaningful insights and assess data quality before applying machine learning techniques.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing  
- Conduct a comprehensive data quality assessment  
- Explore patterns using EDA techniques  
- Visualize seismic activity trends  
- Build and evaluate basic machine learning models  
- Interpret results and draw conclusions  

---

## 📂 Dataset

The dataset used in this project is a publicly available seismic dataset, which typically includes:

## Dataset Information

The data used in this project is the **Seismic-Bumps Data Set** from the UCI Machine Learning Repository. It describes the seismic activity in a coal mine and is used to predict hazardous seismic events.

### Attribute Information (Data Dictionary)

| # | Column Name | Description | Values/Units |
|:---|:---|:---|:---|
| 1 | **seismic** | Seismic hazard assessment (seismic method) | a (none), b (low), c (high), d (danger) |
| 2 | **seismoacoustic** | Seismic hazard assessment (seismoacoustic method) | a, b, c, d |
| 3 | **shift** | Type of work shift | W (coal-getting), N (preparation) |
| 4 | **genergy** | Energy recorded by the most active geophone | Joules |
| 5 | **gpuls** | Number of pulses recorded by the most active geophone | Count |
| 6 | **gdenergy** | Deviation of energy from the average of previous 8 shifts | Ratio/Numeric |
| 7 | **gdpuls** | Deviation of pulses from the average of previous 8 shifts | Ratio/Numeric |
| 8 | **ghazard** | Hazard assessment based only on the most active geophone | a, b, c, d |
| 9 | **nbumps** | Total number of seismic bumps in the previous shift | Count |
| 10-16 | **nbumps[2-89]** | Number of bumps within specific energy ranges (10^2 to 10^10) | Count |
| 17 | **energy** | Total energy of all seismic bumps in the previous shift | Joules |
| 18 | **maxenergy** | Maximum energy of a single bump in the previous shift | Joules |
| 19 | **class (Target)** | **The result to predict:** 1 = Hazard in next shift, 0 = No hazard | 0 or 1 |

**Source:** [UCI Machine Learning Repository - Seismic-Bumps](https://archive.ics.uci.edu/ml/datasets/seismic-bumps)

---

## 🧹 Data Quality Report

The following checks are performed:

- Missing values analysis  
- Duplicate records detection  
- Outlier identification  
- Data type consistency  
- Noise and anomaly detection  

---

## 🔍 Exploratory Data Analysis (EDA)

EDA includes:

- Distribution analysis (e.g., magnitude, depth)  
- Correlation analysis between variables  
- Time-series analysis of seismic events  
- Geographic visualization of earthquake locations  
- Feature relationships and pattern discovery  

---

## 🤖 Machine Learning

Basic machine learning techniques applied:

### Regression
- Linear Regression (predicting magnitude)

### Classification
- Decision Trees  
- K-Nearest Neighbors (KNN)  
- Random Forest (optional)

---

## 📈 Evaluation Metrics

### Regression Metrics
- RMSE (Root Mean Squared Error)  
- MAE (Mean Absolute Error)  
- R² Score  

### Classification Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone < >