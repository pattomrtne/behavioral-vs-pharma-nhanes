# Predicting Metabolic Syndrome Using NHANES Data

## Overview
This capstone project explores whether behavioral and lifestyle factors alone can predict metabolic syndrome, and whether the inclusion of pharmaceutical use improves model performance. Using NHANES 2017–2020 data, we developed classification models to analyze clinical and lifestyle indicators of metabolic risk.

## Author
- Patricio Martínez  
- University of San Diego | Master of Science in Applied Data Science

## Goals
- Evaluate the predictive value of behavioral features
- Compare models with and without medication variables
- Identify key risk factors contributing to metabolic syndrome

## Data Source
- **NHANES 2017–March 2020**
- Public health survey data with dietary intake, lab values, physical activity, and prescription drug use

## Methodology
1. **Data Cleaning & Feature Engineering**
   - Created insulin resistance flags, lifestyle scores, and drug use indicators
2. **Modeling**
   - Logistic Regression, Random Forest, XGBoost, Support Vector Machine, Multilayer Perceptron
   - GridSearchCV and SMOTE for class balancing
3. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1 Score, AUC
   - Compared models with vs. without medication input

## Results
- Models using behavioral data alone achieved solid predictive accuracy
- Including pharmaceutical use improved model recall and reduced false negatives
- Top predictors included avg_kcal, avg_sugar, avg_fiber, avg_fat, physically_active, med_class_None

## Tools
- Python (pandas, sklearn, xgboost, matplotlib)
- Jupyter Notebook
- GitHub

## Future Work
- Expand to multiple years of NHANES data
- Test deep learning models for better recall
- Develop web-based risk screening tool
