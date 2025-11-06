# feature-engineering-project
Feature Engineering on Employee Attrition Dataset using python pandas, numpy, scikit-learn libraries.

📊 Employee Dataset Feature Engineering Project

This project demonstrates a complete feature engineering pipeline performed on a synthetic employee dataset with 1000+ records. The goal is to take raw, messy, inconsistent data and convert it into a clean, transformed, and machine-learning-ready dataset. The entire workflow covers all essential preprocessing steps used in real-world data science projects, making it perfect for students and beginners.

✅ 📌 Introduction

In real datasets, we often face challenges such as missing values, invalid entries, duplicates, outliers, inconsistent formats, and mixed units. These issues reduce the accuracy of machine learning models.
This project focuses on fixing all such issues step-by-step through:

✔ Data Cleaning
✔ Data Integration
✔ Data Transformation
✔ Data Reduction

After processing, the dataset becomes consistent, standardized, and ready for use in any ML model.

✅ 📁 About the Dataset

The dataset contains employee information such as:

Employee ID

Name

Age

Gender

Education Level

Years of Experience

Salary (in USD / some incorrect INR values)

Bonus Percentage

Performance Rating

Remote Work (Yes/No)

Overtime Hours

Projects Handled

Department

Job Role

Joining Date

Location (City, State, Country)

Attrition (Yes/No)

The dataset was designed with intentional errors to practice feature engineering such as:
✅ Missing values
✅ Unrealistic values (age = 150, salary = 700000, etc.)
✅ Mixed currency units
✅ Noisy overtime hours
✅ Inconsistent date formats
✅ Duplicates
✅ Outliers
✅ Categorical + numerical mix

✅ 🔧 Project Workflow

The project is divided into the following main steps:

1️⃣ Data Cleaning

Handling missing values (mean, median, mode)

Fixing impossible values (negative experience, >65 age, 300+ overtime hours)

Correcting invalid dates

Detecting & converting incorrect INR salaries to USD

Removing duplicate rows

Outlier detection & treatment using IQR

2️⃣ Data Integration

Standardizing column names (lowercase, consistent format)

Fixing unit conflicts (INR → USD)

Removing low-variance columns

Removing highly correlated columns to avoid redundancy

3️⃣ Data Transformation

Label Encoding (gender, education level, attrition, remote work)

One-Hot Encoding (department, job role, location)

MinMax Scaling + Z-Score Standardization

Log transformation for skewed numeric values

Discretization (salary → low, medium, high categories)

4️⃣ Data Reduction

Removing unnecessary columns (name, joining date)

Dimensionality reduction using PCA, preserving 95% variance

Outputting final PCA components

✅ 🛠️ Tools & Libraries Used

Python

Pandas

NumPy

Scikit-Learn

Jupyter Notebook / Python Script
