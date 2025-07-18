# ❤️ Heart Disease Risk Predictor

This project is a **binary classification machine learning model** that predicts whether a person is at risk of heart disease based on several health indicators. It demonstrates skills in **data cleaning**, **EDA**, and modeling using **Logistic Regression** and **Decision Tree** classifiers.

---

## 📌 Project Objectives

- Clean and preprocess the dataset
- Explore the data visually using plots and statistics
- Build and evaluate classification models
- Compare model performance and provide interpretation

---

## 📊 Dataset Features

| Feature             | Description                                     |
|---------------------|-------------------------------------------------|
| Age                 | Age of the individual                          |
| RestingBP           | Resting blood pressure                         |
| Cholesterol         | Serum cholesterol level (mg/dl)                |
| FastingBS>120       | Fasting blood sugar > 120 mg/dl (Yes/No)       |
| ExerciseAngina      | Angina induced by exercise (Yes/No)            |
| HeartDisease        | Target: 1 (Disease), 0 (No Disease)            |

---

## 🧹 Data Cleaning Steps

- Removed rows with invalid or missing `HeartDisease` labels
- Filled missing numeric values with **median**
- Converted categorical values (`Yes/No`) to numeric (`1/0`)
- Detected and visualized outliers

---

## 📈 Exploratory Data Analysis (EDA)

- **Boxplots** for `Age`, `Cholesterol`, `RestingBP`
- **Heatmap** to visualize correlations
- **Histograms** with KDE for feature distributions
- **Countplots** and **Violinplots** for categorical impact
- **Pairplot** for visualizing class separation

---

## 🤖 Machine Learning Models

- **Logistic Regression**
- **Decision Tree Classifier**

### Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## ✅ Final Report

Both models were evaluated using common classification metrics. A comparison was made on:
- Overall accuracy
- Ability to detect positive cases (Recall)
- Feature importance interpretation

---

## 🛠️ Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib & Seaborn

---

## 📁 File Structure

