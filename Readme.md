# 🤖 Personality Prediction Using Machine Learning

This project was part of the *Kagal Competition, where the goal was to predict whether a person is an **Introvert* or *Extrovert* using behavioral and social traits from a dataset of 20,000+ rows.

## 👥 Team Members
- Vedant Tarate
- Ayush Nagras

---

## 📌 Problem Statement
Given a dataset with features like stage fear, time spent alone, friend circle, social event attendance, etc., predict the personality type of a person as *Introvert* or *Extrovert*.

---

## 🧾 Features Used
- stage_fear
- drained_after_socializing
- time_spend_alone
- social_event_attendance
- going_outside
- friend_circle
- post_frequency

---

## 🔍 Steps & Methodology

### 1. Exploratory Data Analysis (EDA)
- Identified distributions, null values, and relationships between features.

### 2. Missing Value Handling
- For numeric columns with *>10% missing values, used **MICE (Multivariate Imputation by Chained Equations)*.
- Used *mean imputation* where missing data was less significant.

### 3. Data Transformation
- Applied *Log Transformation* for right-skewed data.
- Used *Yeo-Johnson Transformation* for uneven distributions to normalize the dataset.

### 4. Outlier Handling
- Managed outliers using *Binning* technique.

### 5. Model Training
- Model used: *Logistic Regression*
- Dataset split into training (20,000 rows) and test (6,000 rows).

---

## 🏁 Results

| Metric | Score |
|--------|-------|
| Accuracy (20% test data) | 97.6% |
| Final Accuracy (full test data) | 96.8% |
| Final Rank | 2305 |

---

## 🧠 Learnings
- *MICE is effective* for imputing missing values when >10% of data is missing in a numeric column.
- *Data transformation is necessary* to normalize distributions and improve model performance.
- Outlier handling and proper EDA significantly affect prediction accuracy.

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

---

## 📂 Folder Structure (if applicable)
