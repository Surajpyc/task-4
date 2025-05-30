
# Logistic Regression Classifier - Breast Cancer Dataset

## Objective
Build a binary classifier using logistic regression to predict if a tumor is malignant or benign.

## Dataset
- Breast Cancer Wisconsin (Diagnostic) dataset
- Target: `diagnosis` (M = Malignant, B = Benign)

## Steps:
1. Preprocess the data (drop columns, encode target)
2. Train/test split and feature scaling
3. Train Logistic Regression model
4. Evaluate using confusion matrix, classification report, ROC-AUC
5. Visualize ROC curve and sigmoid function

## Tools Used
- Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## Results
- **Accuracy**: ~97%
- **ROC-AUC**: ~0.997

## How to Run
Place `data.csv` in the same directory as the notebook and run all cells.
