# CODSOFT_TASK5
#  CREDIT CARD FRAUD DETECTION

## Author : IMAM HUSSAIN B 
## Batch: APRIL BATCH B23  
## Domain: Data Science

## Project Overview
This project aims to train a classification algorithm to identify fraudulent transactions in a credit card transaction dataset. The goal is to build a model that can classify transactions as either fraudulent or genuine, using various machine learning techniques.

## Dataset
The dataset used in this project is the **Credit Card Fraud Detection** dataset. It contains transaction data with features like time, transaction amount, and anonymized variables (V1, V2, ..., V28), along with a target variable `Class`, which indicates whether the transaction is fraudulent (`1`) or genuine (`0`).

## Libraries Used
- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization
- `imblearn` for handling imbalanced data
- `sklearn` for machine learning models and metrics

## Data Visualization:
The distribution of features is visualized using histograms. Additionally, a bar chart is plotted to display the class distribution of fraudulent vs. genuine transactions.

## Handling Imbalanced Dataset
Since the dataset is highly imbalanced, the NearMiss technique is used to undersample the majority class (genuine transactions), balancing the dataset.

## Logistic Regression Model
A logistic regression model is trained on the resampled data.

## Model Evaluation
The model's performance is evaluated using precision, recall, F1-score, and the confusion matrix.


#### Precision: 0.61

#### Recall: 0.56

#### F1-Score: 0.59

## Confusion Matrix:

#### Legitimate transactions correctly predicted: 56829

#### Legitimate transactions wrongly flagged as fraud: 35

#### Fraudulent transactions correctly predicted: 55

#### Fraudulent transactions missed: 43
