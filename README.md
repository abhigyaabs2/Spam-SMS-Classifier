
# Spam Email Classifier using Logistic Regression

## 🚀 Overview

This project is a **Spam Email Classifier** built using **Logistic Regression**, a popular classification algorithm in Machine Learning. The goal is to automatically classify emails as either **Spam (1)** or **Ham (0)** based on their content.

It’s a part of my Week 2 Mini Project, and it demonstrates the end-to-end process of building a machine learning model — from data loading and preprocessing to model training, evaluation, and performance analysis.

---

## 📂 Dataset

The dataset used is the famous **SMS Spam Collection Dataset**, which contains 5,572 labeled messages collected from various sources.

- **0** → Ham (Not Spam)
- **1** → Spam

Each entry contains:
- A label (`ham` or `spam`)
- A text message

---

## 🔧 Tech Stack

- **Programming Language**: Python 🐍
- **Libraries Used**:
  - `pandas` and `numpy` for data manipulation
  - `scikit-learn` for modeling and evaluation
  - `matplotlib` and `seaborn` for visualizations

---

## 📌 Project Steps

1. **Load and Explore Dataset**
   - Clean and analyze the data
2. **Data Preprocessing**
   - Convert labels (ham/spam → 0/1)
   - Clean the text: lowercase, remove punctuation, optional stemming
3. **Feature Extraction**
   - Use `CountVectorizer` to convert text into numerical features
4. **Train-Test Split**
   - Split data into training and test sets (e.g., 80/20)
5. **Model Training**
   - Train a Logistic Regression model on the training data
6. **Model Evaluation**
   - Calculate accuracy, confusion matrix, precision, recall, F1-score
   - Visualize performance using seaborn and matplotlib
7. **Analysis**
   - Interpret the results and suggest improvements

---

## 📊 Model Performance

- **Accuracy**: 98.39%
- **Precision (Spam)**: 97%
- **Recall (Spam)**: 91%
- **F1-Score (Spam)**: 94%

✅ The model performs very well, especially in correctly identifying ham messages, with only a few spam emails missed.

---

## 📈 Visualization

- Confusion Matrix Heatmap

---


