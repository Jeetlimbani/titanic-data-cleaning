# Titanic Survival Prediction – Data Cleaning Project

## 📌 Overview

This project focuses on **data cleaning and preprocessing** using the Titanic dataset.

The main purpose of this project is to understand how raw data can be cleaned and prepared before applying Machine Learning algorithms.

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

## 📊 Dataset

The project uses the **Titanic Dataset**, which contains information about passengers who traveled on the Titanic.

Important features include:

* Passenger ID
* Survival status
* Passenger class
* Name
* Sex
* Age
* Number of siblings/spouses
* Number of parents/children
* Ticket
* Fare
* Cabin
* Port of embarkation

## 🔄 Data Cleaning & Preprocessing

The following steps were performed:

1. Loaded the Titanic dataset using Pandas.
2. Checked the dataset shape and basic information.
3. Generated basic statistical summaries.
4. Checked for missing values.
5. Handled missing `Age` values using the median.
6. Handled missing `Embarked` values using the mode.
7. Removed the `Cabin` column because it contained many missing values.
8. Converted the `Sex` column into numerical values using Label Encoding.
9. Converted the `Embarked` column into numerical columns using One-Hot Encoding.
10. Checked the cleaned dataset for remaining missing values.
11. Visualized the age distribution of passengers using a histogram.
12. Saved the cleaned dataset as a new CSV file.

## 📈 Visualization

An **Age Distribution** histogram was created to understand the distribution of passenger ages in the Titanic dataset.

## 📁 Project Files

* `titanic.csv` – Original Titanic dataset
* `titanic_cleaned.csv` – Cleaned and preprocessed dataset
* `titanic_data_cleaning.py` – Python data cleaning script
* `README.md` – Project documentation

## 🎯 Learning Objectives

Through this project, I learned and practiced:

* Data loading with Pandas
* Dataset exploration
* Basic statistical analysis
* Missing value handling
* Median and mode imputation
* Categorical data encoding
* Label Encoding
* One-Hot Encoding
* Data visualization with Matplotlib
* Saving cleaned datasets
* Basic Machine Learning data preprocessing

## 🚀 Future Scope

This cleaned dataset can be used for the next stage of the project:

**Titanic Survival Prediction using Machine Learning**

Future steps can include:

* Feature selection
* Train-test splitting
* Training Machine Learning models
* Model evaluation
* Comparing different algorithms
* Predicting passenger survival

## 👨‍💻 Author
Jeet Limbani


⭐ This project was created as part of my learning journey in **Python, Data Analysis, and Machine Learning**.
