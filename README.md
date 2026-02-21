# Titanic Dataset Cleaning and Preprocessing

## Overview

This project focuses on cleaning and preprocessing the Titanic dataset to improve data quality and prepare it for analysis and machine learning.

The dataset was processed using Python, Pandas, and Scikit-learn in Jupyter Notebook.

---

## Objectives

* Handle missing values
* Encode categorical variables
* Normalize numerical features
* Perform correlation analysis
* Create a clean dataset ready for machine learning

---

## Dataset

The dataset used is the Titanic dataset from the Seaborn library.

It contains passenger information such as:

* PassengerId
* Survival status
* Passenger class
* Sex
* Age
* Fare
* Cabin
* Embarkation port

---

## Data Cleaning Steps

### 1. Handling Missing Values

* Age → Filled using median
* Cabin → Filled with "Unknown"
* Embarked → Filled using mode

### 2. Encoding Categorical Variables

* Sex → Converted into numerical format
* Embarked → One-hot encoded

### 3. Feature Normalization

* Fare → Normalized using MinMaxScaler

### 4. Correlation Analysis

* Correlation heatmap created to understand feature relationships

---

## Files in this Repository

* `titanic_cleaned.csv` → Cleaned dataset
* `titanic_cleaning.ipynb` → Jupyter Notebook with full code
* `README.md` → Project documentation

---

## Tools and Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Result

The dataset is now:

* Clean
* Consistent
* Free from missing values
* Properly encoded
* Ready for analysis and machine learning

---

## Author

GitHub: YourGitHubUsername
Project: Titanic Data Cleaning Assignment

---

## Conclusion

This project demonstrates essential data preprocessing techniques required in data science workflows, including handling missing values, encoding categorical data, normalization, and data preparation for machine learning.
