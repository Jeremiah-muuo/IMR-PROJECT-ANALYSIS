# Infant Mortality Rate (IMR) Analysis – Kenya (KDHS 2022)

**R project** for cleaning, modeling, and visualizing KDHS 2022 data to identify risk factors and predict infant mortality across Kenya's 47 counties.

## 📌 Overview

This repository contains an end‑to‑end analysis of infant mortality using the **2022 Kenya Demographic and Health Survey (KDHS)**.  
The workflow includes:

- Data cleaning & preprocessing  
- Exploratory data analysis (EDA)  
- Variable transformation & feature engineering  
- Predictive modeling (logistic regression, random forest, KNN, etc.)  
- County‑level risk mapping  
- Model evaluation (ROC, AUC, confusion matrices)

## 📁 Files

- `Do_file_R_Project.R` – Main R script (cleaning, modeling, visualization)  
- `README.md` – Project documentation

## 🔧 Requirements (R packages)

```r
install.packages(c("tidyverse", "haven", "dplyr", "ggplot2", 
                   "caret", "randomForest", "pROC", "rpart", 
                   "sf", "tmap", "gtsummary"))
