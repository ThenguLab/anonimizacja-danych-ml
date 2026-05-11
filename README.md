# Security of Training Data – Analysis of Anonymization Techniques

Postgraduate diploma project focused on the impact of data anonymization techniques on machine learning model performance.

## Project Overview

This project analyzes how selected anonymization methods affect the quality and effectiveness of machine learning models trained on sensitive data.

The study focuses on two widely used privacy-preserving techniques:

- k-anonymity
- l-diversity

The experiments were conducted using a Random Forest classification model trained on multiple versions of the dataset:
- original (non-anonymized) data,
- data anonymized with k-anonymity,
- data anonymized with k-anonymity and l-diversity.

The goal of the project is to evaluate the trade-off between:
- data privacy,
- information utility,
- predictive model performance.

---

## Technologies Used

- Python
- Scriptbook environment
- Scikit-learn
- Pandas
- NumPy

---

## Dataset

The project uses a dataset based on demographic and socio-economic attributes commonly applied in income classification tasks.

Sensitive and quasi-identifying attributes were anonymized before model training.

---

## Evaluation Metrics

The machine learning models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

---

## Research Scope

The project includes:
- data preprocessing,
- implementation of anonymization techniques,
- machine learning model training,
- comparative analysis of model performance,
- interpretation of privacy-utility trade-offs.

---

## Academic Purpose

This repository was created as part of a postgraduate diploma project focused on privacy-preserving machine learning and data security.
