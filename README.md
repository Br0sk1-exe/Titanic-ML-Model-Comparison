```markdown
# 🚢 Titanic ML Model Comparison

An end-to-end Machine Learning project that predicts passenger survival on the Titanic dataset while comparing the performance of multiple classification algorithms.

---

## 📌 Project Overview

This project explores the famous Titanic dataset by performing:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Model Training
- Model Evaluation
- Model Comparison

The objective is to compare different machine learning algorithms and identify the best-performing model for predicting passenger survival.

---

## 📊 Dataset

The dataset contains passenger information such as:

- Passenger Class (Pclass)
- Sex
- Age
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Fare
- Embarked Port
- Survival Status (Target Variable)

---

## 🛠 Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
  - PassengerId
  - Name
  - Ticket
  - Cabin

- Filled missing values
  - Age → Median
  - Embarked → Mode

- Encoded categorical variables
  - Sex → Binary Encoding
  - Embarked → One-Hot Encoding

- Standardized features for Logistic Regression

---

## 📈 Exploratory Data Analysis

Visualizations included:

- Survival Count
- Survival Rate by Gender
- Survival Rate by Passenger Class

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost

---

## 📊 Model Performance

| Model | Accuracy |
|--------|-----------|
| Logistic Regression | **81%** |
| Decision Tree | **79%** |
| Random Forest | **82%** |
| XGBoost | **84%** |

🏆 **Best Performing Model:** XGBoost

---

## 📏 Evaluation Metrics

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- XGBoost

---

## 📂 Project Structure

```

Titanic-ML-Model-Comparison/
│
├── project.ipynb
├── train.csv
├── README.md
└── requirements.txt

```

---

## 🎯 Key Learnings

Through this project, I learned:

- Data preprocessing techniques
- Handling missing values
- Feature encoding
- Feature scaling
- Exploratory Data Analysis (EDA)
- Logistic Regression
- Decision Trees
- Random Forests
- XGBoost
- Model evaluation using multiple metrics
- Comparing different machine learning models

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Feature engineering
- Cross-validation
- ROC-AUC Curve
- Feature Importance Visualization
- SHAP Explainability

---

## 👨‍💻 Author

**Shwetank Swarup**

If you found this project useful, consider giving it a ⭐ on GitHub!
```
