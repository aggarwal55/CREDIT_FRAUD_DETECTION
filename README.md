# Credit Card Fraud Detection Using Machine Learning

## Abstract
Credit card fraud is a growing global concern, costing billions of dollars annually. Machine learning offers a powerful approach to detect such fraud by uncovering hidden patterns in transaction data. This project focuses on developing a machine learning model trained on historical transaction data to identify fraudulent transactions. The model was trained and tested on a real dataset and evaluated for its accuracy on unseen data.

*Keywords:* Credit Card Fraud Detection, Fraudulent Transactions, KNN, Logistic Regression, SVM, Decision Tree

---

## Overview
With the rising number of credit card users worldwide, protecting customers from fraud has become increasingly important. Reports show that credit card fraud incidents surged by nearly 45% in 2020. Fraud generally occurs in two ways: (1) opening new accounts using stolen identities, or (2) using an existing cardholder’s account without authorization. The rapid increase in such activities motivated us to build a data-driven system to detect fraudulent transactions automatically using machine learning.

---

## Project Goals
The primary goal of this project is to accurately detect fraudulent credit card transactions and minimize false positives. Multiple machine learning algorithms were implemented and compared to determine the best performer. The comparison was supported with evaluation metrics and visualizations to identify the most effective model for fraud detection.

---

## Dataset
The dataset used was sourced from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and contains 284,808 transactions carried out by European cardholders over two days.  
It includes 31 features — 28 anonymized numeric variables transformed using PCA, along with Time, Amount, and Class (where 1 = Fraud, 0 = Legitimate).

---

## Algorithms Implemented
1. *K-Nearest Neighbors (KNN)*  
2. *Logistic Regression (LR)*  
3. *Support Vector Machine (SVM)*  
4. *Decision Tree (DT)*  

---

## Future Work
Future enhancements could include testing the model on multiple datasets, experimenting with different train/test splits, and adding additional features (e.g., geolocation data) to detect suspicious transactions more effectively.

---

## Conclusion
The project successfully implemented four machine learning models and compared their performance. *KNN and Decision Tree produced the highest accuracy*, making them strong candidates for practical fraud detection systems. These results show that machine learning can significantly improve the reliability and security of credit card transactions.

////////////YE README ME DAL DENA
