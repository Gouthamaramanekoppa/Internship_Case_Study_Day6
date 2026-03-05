# Internship_Case_Study_Day6

Overview

Day 6 focuses on identifying potential AI/ML approaches that can be used to solve the credit card fraud detection problem. The goal is to shortlist 3–4 suitable techniques for further technical comparison and feasibility analysis.

Since fraud detection is a binary classification problem with highly imbalanced data, selected approaches must handle imbalance effectively while maintaining high recall and acceptable precision.

Problem Nature Recap
Binary classification (Fraud / Non-Fraud)
Highly imbalanced dataset (<1% fraud cases)
Real-time detection requirement
Need to minimize financial loss and false positives

Identified AI/ML Approaches

Based on industry research and problem characteristics, the following approaches were shortlisted:

Logistic Regression (Baseline Model)

Supervised Learning (Linear Model)
Why Selected:
Simple and interpretable
Provides probability scores
Fast inference time
Common industry baseline

Advantages:
Easy to implement
Low computational cost
Interpretable coefficients

Limitations:
Limited ability to capture nonlinear relationships
Performance may drop for complex fraud patterns

Random Forest

Type:
Ensemble Learning (Bagging)

Why Selected:
Handles nonlinear relationships
Robust to overfitting
Works well with imbalanced datasets (with class weighting)

Advantages:
High accuracy
Feature importance ranking
Good generalization

Limitations:
Larger model size
Slower inference compared to logistic regression

Gradient Boosting (XGBoost)

Type: Ensemble Learning (Boosting)

Why Selected:
State-of-the-art performance in structured datasets
Handles class imbalance effectively
Strong performance in fraud detection competitions

Advantages:
High predictive power
Built-in regularization
Handles missing values

Limitations:
Hyperparameter tuning required
Higher computational cost

Neural Networks (Multi-Layer Perceptron)

Type: Deep Learning
Why Selected:
Captures complex nonlinear patterns
Learns hidden representations
Adaptable to evolving fraud behavior

Advantages:
Flexible architecture
Strong modeling capability

Limitations:
Requires more data
Risk of overfitting
Less interpretable


Isolation Forest (Anomaly Detection)
Used when fraud labels are limited.  
Detects anomalies rather than relying purely on supervised learning.

Initial Comparison Matrix (Preliminary)
| Model | Interpretability | Accuracy Potential | Speed | Complexity |
|-------|-----------------|-------------------|-------|------------|
| Logistic Regression | High | Moderate | Very Fast | Low |
| Random Forest | Medium | High | Moderate | Medium |
| XGBoost | Medium | Very High | Moderate | High |
| Neural Network | Low | High | Slower | High |


