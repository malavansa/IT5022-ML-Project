# 💳 Credit Card Default Prediction

## Project Overview

This project aims to predict whether a credit card holder will default on their next payment using a sample dataset. It explores various preprocessing techniques, supervised classification algorithms, and evaluation metrics to build and assess predictive models.

---

##  Workflow Summary

1. **Data Cleaning**  
   - Removed missing values and handled outliers  
   - Basic sanity checks and formatting

2. **Exploratory Data Analysis (EDA)**  
   - Visualized feature distributions and target imbalance  
   - Investigated correlations and multicollinearity

3. **Preprocessing**  
   - Feature selection and extraction  
   - Scaling and normalization  
   - PCA for dimensionality reduction  
   - SMOTE for handling class imbalance

4. **Modeling**  
   - Trained multiple classifiers: Logistic Regression, SVM, Random Forest, XGBoost  
   - Used different dataset variants (scaled, balanced, PCA, feature engineered)

5. **Evaluation**  
   - Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix  
   - Compared performance across datasets and models

---

## 📊 Key Findings

- SMOTE improved recall for the minority class but introduced overfitting in some models  
- SVM and ensemble methods showed moderate performance  
- The dataset size and limited feature diversity may have constrained model effectiveness  
- Future improvements could include more behavioral and transactional features

---

## 📁 Folder Structure

```
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for EDA, preprocessing, modeling
├── reports/               # Evaluation results and visualizations
├── README.md              # Project overview
```

---

## 🚀 How to Run

1. Clone the repo  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```



