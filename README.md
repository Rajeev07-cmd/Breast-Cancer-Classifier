# Breast-Cancer-Classifier

# 🧠 Breast Cancer Diagnosis Classifier

This project builds a machine learning model to predict whether a breast tumor is **benign** or **malignant** using features derived from digitized images of fine needle aspirates (FNA) of breast masses.

## 🎯 Objective
The goal is to train an interpretable and accurate classification model using **Logistic Regression** and identify the most important features contributing to the diagnosis.

## 🔍 Key Steps
- **Exploratory Data Analysis (EDA)**: Analyze feature distributions, class balance, and feature correlations.
- **Feature Selection**: Apply `SelectKBest` with `f_classif` to select the top 10 most relevant features.
- **Model Training**: Use Logistic Regression for classification on both full and selected feature sets.
- **Model Evaluation**:
  - Accuracy & F1-score
  - Confusion Matrix visualization
  - ROC Curve & AUC Score
- **Feature Importance**: Examine model coefficients to interpret which features impact predictions most.

## 🛠 Technologies Used
- Python
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook / Google Colab

## 📦 Deliverables
- Jupyter Notebook: Full code from data loading to model evaluation.
- Visuals: Heatmap, Confusion Matrix, ROC Curve, and Feature Importance Bar Plot.
- Summary report: Model performance overview and insights from feature importance.
