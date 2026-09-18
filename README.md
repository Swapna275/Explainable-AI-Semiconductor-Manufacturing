# Explainable AI for Semiconductor Manufacturing

## Research Project

This project investigates the use of machine learning and explainable artificial intelligence (XAI) for semiconductor manufacturing failure prediction, root-cause analysis, and yield improvement.

## Objectives

- Predict semiconductor manufacturing failures using machine learning.
- Identify important process features associated with failures.
- Apply Explainable AI to interpret model predictions.
- Perform data-driven root-cause analysis.
- Investigate potential opportunities for yield improvement.

## Dataset

The study uses the SECOM semiconductor manufacturing dataset, containing manufacturing process measurements and pass/fail outcomes.

## Machine Learning Models

The project evaluates:

- Logistic Regression
- Random Forest
- XGBoost

Because semiconductor failure data are highly imbalanced, model performance is evaluated using metrics including ROC-AUC, PR-AUC, precision, recall, and F1-score.

## Explainable AI

SHAP (SHapley Additive exPlanations) is used to identify influential process features and interpret model predictions.

Statistical analysis is also used to examine whether identified features show evidence of association with manufacturing failures.

## Root-Cause Analysis

The analysis combines:

1. Machine learning prediction
2. SHAP-based feature importance
3. Failure-rate analysis
4. Statistical validation
5. Multi-sample investigation

The resulting evidence is used to identify candidate features associated with semiconductor manufacturing failures.

## Key Findings

The analysis demonstrates that machine learning can provide useful predictive signals for semiconductor manufacturing failures, while explainability methods can help identify process variables associated with failure outcomes.

The study emphasizes that statistical and machine-learning evidence should be interpreted as data-driven evidence of association rather than direct proof of physical causality.

## Project Structure

- `Semiconductor_RCA_Final_Analysis_Backup (1).ipynb` — completed research notebook
- Research thesis/document — detailed methodology, experiments, results, and discussion

## Technologies

Python | Pandas | NumPy | Scikit-learn | XGBoost | SHAP | Matplotlib

## Research Focus

**Explainable AI • Semiconductor Manufacturing • Failure Prediction • Root-Cause Analysis • Yield Improvement • Machine Learning**
