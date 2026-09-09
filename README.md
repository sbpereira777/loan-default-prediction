# Loan Default Prediction

## Overview
This project predicts loan default using Logistic Regression, with a focus on balancing statistical modeling and business decision-making.

---

## Workflow
- Data Cleaning (removed unrealistic values)
- Exploratory Data Analysis (boxplots, correlation)
- Multicollinearity check using VIF
- Logistic Regression with L2 Regularization
- ROC-AUC evaluation
- Threshold tuning (0.5 → 0.3)
- Model interpretation using Odds Ratios

---

## Results
- Accuracy: ~89%
- ROC-AUC: 0.95
- Recall improved from 0.73 → 0.87

---

## Key Insight
Instead of optimizing only accuracy, the model prioritizes **recall for defaulters**, aligning with real-world credit risk objectives.

## How to Run
1. Download the dataset
2. Open the notebook in Jupyter
3. Run all cells sequentially
