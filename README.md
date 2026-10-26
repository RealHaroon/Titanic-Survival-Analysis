

# 📄 Prodigy InfoTech Data Science Internship — Task 02


## 🚢 Titanic Data Cleaning & Exploratory Data Analysis

This project focuses on performing **Data Cleaning and Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover survival patterns and relationships between passenger attributes.

---

## 📊 Dataset Information

* Total Records: **891**
* Total Features: **12**
* Dataset: Kaggle Titanic (train.csv)

Features include passenger demographics, ticket details, class, fare, and survival status.

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Checked for duplicate records → None found
* Identified missing values in:

  * Cabin
  * Age
  * Embarked
* Handling strategy:

  * **Cabin column dropped** (excessive null values)
  * **Age filled with median**
  * **Embarked filled with mode**

---

## ⚙️ Feature Engineering

New features created to enhance analysis:

* **FamilySize** = SibSp + Parch + 1
* **IsAlone** → Indicates passengers traveling alone

These features helped analyze the impact of family presence on survival.

---

## 📈 Exploratory Analysis & Insights

Key findings from the analysis:

* Survival Rate: ~39% survived, ~61% did not
* Female survival rate was significantly higher than males
* 1st Class passengers had the highest survival probability
* Children showed better survival chances
* Higher ticket fare correlated with higher survival
* Majority passengers were young adults
* Age distribution was right-skewed

---

## 🛠️ Tools & Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📌 Objective

To practice real-world data preprocessing and exploratory analysis by identifying trends, relationships, and survival patterns within the Titanic dataset.

---

