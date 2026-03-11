Chemical Toxicity Prediction
A machine learning project to predict whether chemical compounds are toxic or non-toxic using molecular descriptors.

Overview
This project builds a classification model to identify toxic chemicals early in drug discovery and environmental safety screening. The dataset contains 171 compounds with 1203 molecular features.

Key challenges addressed:
High-dimensional data (1203 features, 171 samples)
Class imbalance (67% Non-Toxic, 33% Toxic)

Key Results
Features reduced: 1203 → 50 (95.8% reduction)
Best model: Random Forest
Test ROC-AUC: 0.572
Toxic detection rate: 91% at optimized threshold

Dataset
Samples: 171 chemical compounds
Features: 1203 molecular descriptors
Target: Toxic (56) vs Non-Toxic (115)

Methods
Feature selection: ANOVA, Mutual Information, Random Forest, RFE
Models: Logistic Regression, Random Forest, Gradient Boosting, SVM, KNN
Evaluation: 5-fold stratified cross-validation

Quick Start
bash
# Clone repository
git clone https://github.com/Kimmystarrs/toxicity.git

# Run notebook
jupyter notebook notebooks/toxicity_analysis.ipynb

Kimberly Otieno - otienoeyvonne@gmail.com
