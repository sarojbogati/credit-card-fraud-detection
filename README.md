# Credit Card Fraud Detection using Machine Learning

## Project Overview
This project builds machine learning models to detect fraudulent credit card transactions using a highly imbalanced dataset.

Fraud detection is a critical problem in financial systems because fraudulent transactions are rare but can cause significant financial loss.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset contains anonymized credit card transactions with 284,807 observations and 31 features.

Fraudulent transactions represent only a very small percentage of the data, making this a highly imbalanced classification problem.

## Methodology
1. Data exploration and preprocessing
2. Class imbalance analysis
3. Feature scaling
4. Machine learning model training
5. Model evaluation using fraud-focused metrics

## Models Used
- Logistic Regression
- Random Forest

## Key Findings

- The dataset is highly imbalanced, with fraud cases representing less than 1% of transactions.
- Logistic Regression achieved high recall but produced many false positives.
- Random Forest achieved a better balance between precision and recall.
- Random Forest provided the strongest overall fraud detection performance for this dataset.

## Project Structure

credit-card-fraud-detection  
│  
├── credit_card_fraud_detection.ipynb  
├── fraud_model_comparison.csv  
└── README.md
