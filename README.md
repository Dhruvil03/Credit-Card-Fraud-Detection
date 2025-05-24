# 💳 Credit-Card-Fraud-Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. By analyzing transaction patterns, we build models that distinguish between legitimate and fraudulent activity, helping financial institutions mitigate risk.

## 📁 Dataset

The dataset used is the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains:

- **Features**: 30 anonymized variables (V1-V28), Time, and Amount
- **Target**: `Class` (0 = Legitimate, 1 = Fraudulent)

> ⚠️ Dataset is highly imbalanced: Only ~0.17% of transactions are fraudulent.

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Imbalanced-learn 

## 🔍 Project Workflow

1. **Data Preprocessing**:
   - Checked for missing values
   - Scaled `Amount` and `Time` features
   - Split dataset into training and test sets

2. **Exploratory Data Analysis (EDA)**:
   - Distribution of classes
   - Correlation heatmaps
   - Class imbalance visualization

3. **Model Training**:
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
   - XGBoost

4. **Imbalance Handling**:
   - Used **SMOTE** (Synthetic Minority Oversampling Technique)

5. **Evaluation Metrics**:
   - Confusion Matrix
   - Precision, Recall, F1-Score

## 📈 Results

- Best performing model achieved high recall while maintaining precision
- Emphasized minimizing false negatives (undetected fraud)
