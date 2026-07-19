# Titanic Survival Prediction Pipeline

This project implements an end-to-end machine learning pipeline for the Titanic dataset, focusing on reproducibility and professional workflow standards.

## Workflow Overview
The pipeline follows a standard data science lifecycle:
* **Data Prep**: Imputed missing values (median for numeric, most-frequent for categorical) and standardized features.
* **Encoding**: Used One-Hot Encoding for categorical features[cite: 1].
* **Modeling**: Built a Logistic Regression classifier as a transparent baseline[cite: 1].
* **Evaluation**: Assessed performance using Classification Report, Confusion Matrix, and ROC-AUC[cite: 1].
* **Validation**: Performed 5-fold cross-validation to ensure model reliability[cite: 1].
* **Persistence**: Saved the final model as `model.joblib` for future reuse[cite: 1].

## Key Results
* **ROC-AUC**: 0.848 +/- 0.014 (via 5-fold CV)[cite: 1].
* **Model**: Logistic Regression[cite: 1].

## Technologies Used
* Python, Pandas, Scikit-Learn, Matplotlib, Joblib[cite: 1].

## How to use
1. Clone this repository.
2. Ensure `titanic.csv` is in the directory[cite: 1].
3. Run the notebook to see the full pipeline, from data cleaning to model persistence[cite: 1].
