# 🏦 Loan Approval Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting loan approval status using Machine Learning classification algorithms. It explores financial and personal applicant information to identify patterns that influence loan approval decisions.

Developed as part of the **CSE422 – Artificial Intelligence** course project, this study implements and compares three supervised machine learning algorithms: Logistic Regression, Decision Tree, and Neural Network.

The project aims to analyze applicant characteristics, preprocess financial data, train predictive models, and evaluate their performance using different classification metrics.

## 🎯 Project Objectives

- Analyze loan applicant data through Exploratory Data Analysis (EDA).
- Identify relationships and correlations between dataset features.
- Perform data preprocessing and feature transformation.
- Train multiple machine learning classification models.
- Compare model performance using accuracy, precision, recall, F1-score, and ROC-AUC.
- Identify the most effective model for loan approval prediction.

## 🛠️ Technologies & Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🤖 Machine Learning Algorithms

This project implements three classification algorithms:

1. **Logistic Regression** – A supervised classification algorithm used as a baseline predictive model.
2. **Decision Tree Classifier** – A tree-based algorithm that makes predictions through decision rules.
3. **Neural Network (MLP Classifier)** – A multilayer perceptron model designed to learn complex patterns from applicant data.

## 📊 Dataset Features

The dataset includes applicant information such as:

- Person Age
- Person Gender
- Person Education
- Person Income
- Employment Experience
- Home Ownership
- Loan Amount
- Loan Intent
- Loan Interest Rate
- Loan Percentage of Income
- Credit History Length
- Credit Score
- Previous Loan Defaults

**Target Variable:** `loan_status`

## ⚙️ Project Workflow

1. Dataset loading and exploration.
2. Exploratory Data Analysis (EDA).
3. Correlation analysis and visualization.
4. Missing-value inspection.
5. Categorical encoding and feature transformation.
6. Feature scaling and normalization.
7. Training and testing dataset splitting.
8. Model training and prediction.
9. Performance evaluation.
10. ROC curve and AUC comparison.

## 📈 Model Performance

| Algorithm | Accuracy | ROC-AUC |
|---|---:|---:|
| Decision Tree | 91.01% | 0.9533 |
| Neural Network | 90.91% | 0.9623 |
| Logistic Regression | 83.13% | 0.8321 |

*Metrics are based on the results recorded in the project notebook.*

## 📉 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- Area Under the Curve (AUC)

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Loan-Approval-Prediction-ML.git
```

### 2. Navigate to the Project Folder

```bash
cd Loan-Approval-Prediction-ML
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Add the Dataset

Place the required loan approval CSV dataset in the project directory.

### 5. Run Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook and execute the cells sequentially.

## 👥 Project Team

**Group:** 12  
**Course:** CSE422 – Artificial Intelligence  
**Institution:** BRAC University

## 📌 Conclusion

This project demonstrates how machine learning algorithms can be applied to loan approval classification. By comparing Logistic Regression, Decision Tree, and Neural Network models, it provides insights into their predictive performance and classification capabilities.

---

⭐ If you find this project interesting, consider giving the repository a star!

**Machine Learning | Data Science | Loan Approval Prediction**
