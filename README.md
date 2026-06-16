# 🍷 Red Wine Quality Prediction Using Machine Learning

## 📖 About the Project

The goal of this project is to predict the quality of red wine using its physicochemical properties with the help of Machine Learning. Instead of relying only on human experts, the model analyzes chemical characteristics such as alcohol, acidity, pH, sulphates, and chlorides to estimate wine quality.

To gain a better understanding of machine learning techniques, the project was implemented using both **Regression** and **Classification** approaches.

---

## 🎯 Problem Statement

Determining wine quality manually requires experienced tasters and can be subjective. This project aims to automate that process by building predictive models that learn from historical data and estimate wine quality based on measurable chemical properties.

---

## 🚀 What This Project Does

* Loads and preprocesses the wine quality dataset.
* Performs Exploratory Data Analysis (EDA) to understand data distribution.
* Identifies relationships between features using correlation analysis.
* Predicts the numerical quality score using a regression model.
* Classifies wines as **Good** or **Bad** using a classification model.
* Evaluates model performance using appropriate metrics.
* Provides business insights based on the most influential features.

---

## 🔍 Data Preprocessing

Before training the models, the dataset was carefully prepared by:

* Checking for missing values
* Removing duplicate records
* Verifying data types
* Separating input features and target variables
* Splitting the dataset into training and testing sets

Proper preprocessing ensures better model performance and reliable predictions.

---

## 📊 Exploratory Data Analysis

EDA was performed to understand the dataset and identify meaningful patterns.

The analysis included:

* Distribution of wine quality scores
* Histograms for numerical features
* Boxplots to detect outliers
* Correlation heatmap to study relationships between variables

This helped identify which chemical properties have the strongest influence on wine quality.

---

## 🤖 Machine Learning Approaches

### 1. Regression

The quality score was treated as a continuous numerical value.

The regression model predicts the exact quality score of a wine sample based on its chemical properties.

The model was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

### 2. Classification

For classification, wine quality was converted into two categories:

* Good Wine → Quality ≥ 7
* Bad Wine → Quality < 7

The classifier predicts whether a wine belongs to the Good or Bad category.

Performance was measured using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📈 Key Observations

* Alcohol content has a strong positive influence on wine quality.
* Higher sulphates are generally associated with better-quality wines.
* High volatile acidity negatively affects wine quality.
* Chemical composition can effectively predict wine quality using machine learning.


---

## 🧠 Skills Demonstrated

Through this project, the following machine learning concepts were applied:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Correlation Analysis
* Regression Modeling
* Classification Modeling
* Model Evaluation
* Data Visualization
* Business Insight Generation

---

## 📚 Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

---
