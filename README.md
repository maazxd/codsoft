# Credit Card Fraud Detection

Machine learning project for detecting fraudulent credit card transactions using Logistic Regression.

## Project Overview

This project uses undersampling technique to handle imbalanced dataset and builds a Logistic Regression model to classify transactions as fraudulent or legitimate.

## Dataset

- Credit card transaction data with 30 features (V1-V28, Time, Amount)
- Highly imbalanced: ~99.8% normal transactions, ~0.2% fraud

## Techniques Used

- **Random Undersampling**: Balancing dataset by randomly sampling normal transactions
- **Logistic Regression**: Binary classification model
- **Train-Test Split**: 80-20 split with stratification

## Model Performance

- Test Accuracy: ~95%
- F1-Score: ~95%
- Successfully detects most fraud cases with minimal false alarms

## Files

- `credit_card.ipynb`: Main Jupyter notebook with complete analysis and model
- `creditcard.csv`: Dataset (excluded from repo due to size)

## Requirements

```
pandas
numpy
scikit-learn
```

## Usage

1. Place the creditcard.csv dataset in the project directory
2. Run all cells in credit_card.ipynb
3. View model performance metrics and confusion matrix

## Author

Data Science Internship Project - CodSoft
