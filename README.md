# AI Based Credit Card Fraud Detection

This project compares three machine learning models for fraud detection across two datasets: the ULB Credit Card Fraud dataset and the PaySim Mobile Money dataset.

## Models Used

- Logistic Regression  
- Random Forest  
- XGBoost  

## Datasets

The datasets used in this project are publicly available:

- ULB Credit Card Fraud Dataset:  
  https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud  

- PaySim Dataset:  
  https://www.kaggle.com/datasets/ealaxi/paysim1  

Due to file size constraints, the datasets are not included in this repository.  
After downloading, place the datasets in the same directory as the notebook before running the code.

## Methodology

The project follows the following pipeline:

1. Data loading and exploration  
2. Data preprocessing  
3. Train/test split  
4. SMOTE applied to training data only  
5. Model training  
6. Evaluation using precision, recall, F1 score, AUC, confusion matrices, and ROC curves  

## Files

- `Card_Fraud_Detection_Project.ipynb` — full Colab notebook containing the implementation  

## Notes

SMOTE was applied only to the training data to avoid data leakage. The test data was kept in its original imbalanced form to provide a realistic evaluation.

## Report

This project was completed as part of the CS3IP Individual Project module at Aston University (2025–2026).
