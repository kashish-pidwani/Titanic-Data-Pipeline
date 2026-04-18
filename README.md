# Titanic Data Pipeline (ETL Project)

## 📌 Overview

This project demonstrates the creation of a complete data pipeline for preprocessing, transformation, and loading (ETL) using Python.

## 🎯 Objective

To automate data cleaning and preparation for machine learning using a structured pipeline.

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Joblib

## ⚙️ Workflow

### 1. Extract

* Loaded Titanic dataset using pandas

### 2. Transform

* Handled missing values
* Encoded categorical features
* Scaled numerical features
* Created new features: **FamilySize** and **IsAlone**

### 3. Load

* Saved processed dataset (`processed_titanic.csv`)
* Saved trained pipeline (`titanic_full_pipeline.pkl`)

## 🤖 Model (Bonus)

* Logistic Regression model used
* Built an end-to-end pipeline for prediction

## 📊 Key Insights

* Female passengers had higher survival rates
* Passengers with family had better survival chances
* Medium-sized families showed higher survival
* Lower class passengers had lower survival

## 📁 Files Included

* `Task1Data-Pipeline.ipynb`
* `Titanic-Dataset.csv`
* `processed_titanic.csv`
* `titanic_full_pipeline.pkl`

## 🚀 Conclusion

This project successfully demonstrates an automated ETL pipeline and shows how structured preprocessing improves data quality and supports machine learning tasks.
