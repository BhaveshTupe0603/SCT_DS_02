# 🚢 Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

## 📌 Project Overview

This repository contains a comprehensive data cleaning and exploratory data analysis (EDA) task performed on the **Titanic dataset** from Kaggle. The project simulates the role of a **Data Analyst Intern**, focusing on preprocessing, handling missing data, visualizing insights, and identifying patterns that influenced passenger survival.

---

## 📂 Dataset Description

The Titanic dataset includes information on passengers such as:

- **PassengerId**: Unique identifier
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name, Sex, Age**
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket, Fare, Cabin, Embarked**
- **Survived**: Target variable (0 = No, 1 = Yes)

Dataset Source: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

---

## 🛠️ Tools & Libraries Used

- **Python** 🐍
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** & **Seaborn** for data visualization
- **Google Colab** for running the notebook

---

## 🧹 Data Cleaning Tasks

- Handled missing values in `Age`, `Embarked`, and dropped `Cabin`.
- Converted categorical variables (`Sex`, `Embarked`) into numerical format.
- Created new features like `FamilySize`.

---

## 📊 Key EDA Insights

- **Gender**: Females had a higher survival rate than males.
- **Class**: 1st class passengers had higher survival chances.
- **Age**: Younger passengers tended to survive more.
- **Embarked**: Passengers from port C had a slightly better survival rate.

Correlation heatmaps and bar plots were used to visualize these patterns.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-eda.git
   cd titanic-eda
