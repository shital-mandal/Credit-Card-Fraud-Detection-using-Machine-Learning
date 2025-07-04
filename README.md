# Credit-Card-Fraud-Detection-using-Machine-Learning
This project implements a machine learning pipeline to detect fraudulent credit card transactions using an anonymized dataset. The aim is to accurately identify fraud cases in highly imbalanced financial data while minimizing false positives.

Problem Statement
Credit card fraud detection is a critical application of machine learning in the financial sector. The dataset used contains real-world transactions with anonymized features (V1–V28), a highly imbalanced class distribution, and a binary target: fraud (1) or non-fraud (0).

Approach and Highlights
Preprocessing & Cleaning
Dataset was clean with no missing values. Scaled Time and Amount using standardization for better model convergence.

Imbalanced Data Handling
Addressed severe class imbalance using SMOTE, generating synthetic minority samples to support fair model training.

Model Evaluation
Trained and compared multiple models including Logistic Regression, Random Forest, and Gradient Boosting.
Chose final model based on a balance of recall, F1-score, and AUC-ROC to optimize fraud detection.

Performance
Achieved strong fraud identification with high recall and precision on test data — ensuring real-time usability in a fraud detection pipeline.

Tools and Libraries Used
Python

pandas, NumPy

scikit-learn

imbalanced-learn (SMOTE)

Matplotlib, Seaborn

Jupyter Notebook
