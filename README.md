# Elastic Net Regression

## 📌 Project Overview

This project demonstrates **Elastic Net Regression**, a regularization technique that combines the strengths of **L1 (Lasso)** and **L2 (Ridge)** penalties.

Using a synthetic dataset generated with Scikit-Learn's `make_regression`, the notebook explains how Elastic Net balances **feature selection** and **coefficient shrinkage**, making it an effective choice when working with datasets containing many correlated features.

---

## 🎯 Objectives

* Understand the fundamentals of Elastic Net Regression
* Learn how L1 and L2 Regularization work together
* Study the effect of alpha and `l1_ratio`
* Compare Elastic Net with Lasso and Ridge Regression
* Analyze coefficient shrinkage and feature selection

---

## 📂 Dataset

**Dataset Used:** `make_regression`

A synthetic regression dataset generated using Scikit-Learn to demonstrate regularization techniques and model behavior.

---

## 📖 Concepts Covered

* Linear Regression
* Elastic Net Regression
* L1 Regularization (Lasso)
* L2 Regularization (Ridge)
* Feature Selection
* Coefficient Shrinkage
* Alpha (Regularization Strength)
* `l1_ratio`
* Bias-Variance Tradeoff

---

## 🛠️ Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## ⚙️ Implementation Steps

### Data Preparation

* Generate a regression dataset using `make_regression`
* Split the data into training and testing sets

### Model Training

* Train the Elastic Net Regression model
* Experiment with different values of alpha and `l1_ratio`

### Model Comparison

* Compare Elastic Net with Linear Regression
* Compare Elastic Net with Ridge Regression
* Compare Elastic Net with Lasso Regression

### Coefficient Analysis

* Observe coefficient shrinkage
* Analyze feature selection behavior
* Study the balance between L1 and L2 penalties

### Visualization

* Plot coefficient changes
* Visualize the impact of regularization strength
* Compare model behavior under different parameter settings

---

## 🔍 Key Observations

* Elastic Net combines the advantages of both Lasso and Ridge Regression.
* The `l1_ratio` controls the balance between L1 and L2 penalties.
* It performs well when features are highly correlated.
* Regularization helps reduce overfitting while maintaining important features.

---

## ✅ Advantages

* Combines feature selection and coefficient shrinkage
* Handles correlated features effectively
* Reduces overfitting
* Produces more stable models than Lasso alone
* Offers flexible control through alpha and `l1_ratio`

---

## 🏁 Conclusion

Elastic Net Regression is a powerful regularization technique that combines the strengths of both Lasso and Ridge Regression. This project provides a practical understanding of how mixed regularization improves model performance, controls complexity, and balances feature selection with coefficient shrinkage.

---

## 💻 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
