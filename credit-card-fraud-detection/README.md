# Credit Card Fraud Detection

Python project using pandas, scikit-learn and plotnine to detect suspicious transactions and evaluate fraud alerts.

## Analysis

- Data validation and duplicate checks
- Chronological training, validation and test splits
- Logistic Regression and Gradient Boosting comparison
- Alert threshold selection using validation data
- 10 charts, feature importance and transaction review queue

## Results

On held-out test data, the selected Logistic Regression model detected 49 of 74 fraudulent transactions and falsely flagged 3 genuine transactions.

- Precision: 94.23%
- Recall: 66.22%
- Average precision: 0.7475

## Files

- .ipynb: complete code and saved outputs
- .png: analysis charts
- .csv: results and analysis tables
- .txt: project summary and prevention recommendations
- .json: run metadata
- .joblib: trained model

## Run

Open the notebook in Google Colab, upload creditcard.csv and run all cells.

[Dataset source: ULB / Worldline](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Limitations

Historical two-day dataset from 2013 with anonymized features. This project proposes verification and review steps; it does not block live payments or demonstrate actual financial savings.
