# A Machine Learning Framework for Predicting Pulmonary Sarcoidosis Using Multi-Cohort Gene Expression

This project develops a machine learning framework to classify pulmonary sarcoidosis using multi-cohort gene expression data.

## Overview
- Integrated multiple GEO datasets (GSE18781, GSE42834, GSE83456)
- Gene matching reduced ~39,000 → 16,622 genes
- Feature selection reduced to 1,000 genes
- Used multiple ML models for classification

## Models Used
- Random Forest (Best Model)
- Support Vector Machine (SVM)
- Logistic Regression
- Gradient Boosting
- KNN
- Naive Bayes

## Results
- Best Model: Random Forest
- Accuracy: ~0.76
- ROC-AUC: ~0.85
- Identified key genes related to immune and inflammatory pathways

## Methods
- Data preprocessing and normalization
- Multi-cohort integration
- Feature selection (SelectKBest)
- Leave-One-Cohort-Out (LOGO) validation

## Files
- Final.ipynb → Full pipeline (preprocessing, modeling, evaluation)

## Reproducibility
This project was developed using Python with:
- pandas
- numpy
- scikit-learn

## Author
Jalen Jackson  
M.S. Biomedical Data Science – Meharry Medical College
