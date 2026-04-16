# 🧪 Glass Classification using Random Forest, Bagging & Boosting

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Ensemble%20Models-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project focuses on classifying glass types using the **Glass dataset** by applying **ensemble machine learning techniques** such as:

- Random Forest Classifier
- Bagging Classifier
- Boosting (AdaBoost)

The workflow includes:
- Exploratory Data Analysis (EDA)
- Data visualization
- Data preprocessing (handling imbalance, scaling, outliers)
- Model building and evaluation
- Comparison of ensemble techniques

---

## 📂 Dataset Information

The dataset contains chemical and physical attributes of glass samples used to classify them into different types.

- Target variable: `Type`
- Features: Refractive index and chemical composition attributes

---

## 🔍 Exploratory Data Analysis (EDA)

Performed detailed analysis to understand dataset structure:

- Checked missing values and duplicates
- Statistical summary of features
- Distribution analysis
- Correlation heatmap

---

## 📊 Data Visualization

Visualizations used:
- Pairplot (feature relationships)
- Boxplots (outlier detection)
- Heatmap (correlation analysis)
- Distribution plots

These helped identify patterns and feature relationships impacting classification.

---

## 🧹 Data Preprocessing

Key preprocessing steps:

- Removed missing values
- Handled duplicates
- Outlier detection using IQR method
- Feature scaling using StandardScaler
- Handled class imbalance using **oversampling**

---

## ⚖️ Handling Imbalanced Data

The dataset was imbalanced across glass types.

### Solution applied:
- Oversampling minority classes using random sampling
- Ensured equal representation of all classes

---

## 🌲 Machine Learning Models

### 1️⃣ Random Forest Classifier
- Built using `sklearn.ensemble.RandomForestClassifier`
- Trained on 80% training data
- Evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1-score

---

### 2️⃣ Bagging Classifier
- Implemented using `BaggingClassifier`
- Base estimator: Random Forest
- Helps reduce variance and improve stability

---

### 3️⃣ Boosting (AdaBoost)
- Implemented using `AdaBoostClassifier`
- Focuses on correcting previous model errors
- Improves overall prediction accuracy

---

## 📈 Model Evaluation Metrics

Models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## ⚔️ Bagging vs Boosting

| Feature        | Bagging                        | Boosting                       |
|----------------|--------------------------------|--------------------------------|
| Training       | Parallel                       | Sequential                     |
| Goal           | Reduce variance                | Reduce bias                    |
| Focus          | Equal weight samples           | Focus on mistakes              |
| Example        | Random Forest                  | AdaBoost, XGBoost              |

---

## 📌 Key Learnings

- How ensemble models improve performance
- Importance of handling imbalanced data
- Feature scaling impact on ML models
- Difference between bagging and boosting
- Practical implementation of classification pipeline

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🚀 How to Run This Project

```bash
# Clone repository
git clone https://github.com/your-username/glass-random-forest-classification-ml.git

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook

---

👩‍💻 Author

Meghana C Varghese
Data Scientist | Machine Learning Enthusiast
