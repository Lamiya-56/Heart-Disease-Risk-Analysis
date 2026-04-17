# Heart-Disease-Risk-Analysis
# 🫀 Heart Disease Risk Analysis & Diagnostic Insights

This project provides a comprehensive **Exploratory Data Analysis (EDA)** on clinical factors influencing heart disease. Using the `heart.csv` dataset, the study investigates how physiological indicators like age, chest pain type (CP), and maximum heart rate (Thalach) correlate with cardiovascular risks.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10_eWdzMMbkTKJM6_kQpE2IHa0bxRVg0n)

## 📌 Project Objectives
The primary goal of this analysis is to identify key predictors of heart disease. Rather than looking at variables in isolation, the project focuses on:
* **Correlation Mapping:** Understanding the interplay between clinical metrics.
* **Risk Profiling:** Identifying high-risk patient segments based on age and symptomatic data.
* **Feature Importance:** Evaluating which indicators (e.g., CP vs. Cholesterol) hold more weight in potential diagnoses.

## 📊 Key Analytical Insights

### 1. Correlation Matrix & Feature Interaction
* **Positive Correlations:** Attributes such as `cp` (chest pain type), `thalach` (maximum heart rate), and `slope` show a significant positive correlation with the `target` variable, identifying them as strong diagnostic predictors.
* **Negative Indicators:** `exang` (exercise-induced angina) and `oldpeak` (ST depression) exhibit inverse relationships, serving as critical "red flags" during clinical assessments.

### 2. Chest Pain (CP) Categorical Analysis
* The data reveals that patients exhibiting **Non-Anginal Pain (CP=2)** and **Atypical Angina (CP=1)** have a substantially higher probability of heart disease compared to those who are asymptomatic (CP=0). 
* This suggests that the *type* of pain is a more reliable predictor than the presence of pain alone.

### 3. Demographic Risk Trends (Age & Health Metrics)
* **Conditional Probability:** By segmenting age into cohorts, the analysis identifies specific "danger zones" where physiological metrics (like heart rate) deviate from healthy norms, providing a more granular view of risk than simple global averages.

## 🛠 Tech Stack
* **Environment:** Google Colab
* **Programming Language:** Python
* **Core Libraries:**
    * `Pandas`: Data manipulation and structural analysis.
    * `Seaborn` & `Matplotlib`: Advanced statistical visualization.
    * `NumPy`: High-level mathematical computations.

## 📂 Dataset Architecture
The `heart.csv` dataset consists of 303 observations with 14 clinical attributes:
- `age`: Patient's age.
- `cp`: Chest pain type (Values: 0, 1, 2, 3).
- `trestbps`: Resting blood pressure.
- `thalach`: Maximum heart rate achieved.
- `target`: Diagnosis of heart disease (0 = No, 1 = Yes).

---
**Specialization:** Data Analytics | Business Intelligence | Statistical Modeling
