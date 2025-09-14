# Loan-approval-automation

Machine Learning-Based Loan Approval Automation: Enhancing Efficiency, Accuracy, and Fairness in Credit Decision-Making

# Loan Approval Automation using Machine Learning

This repository contains the MSc dissertation project:  
**"Machine Learning-Based Loan Approval Automation: Enhancing Efficiency, Accuracy, and Fairness in Credit Decision-Making."**

The project explores the use of **Random Forest**, **XGBoost**, and **ensemble models** (stacking and voting) to automate the loan approval process, improve predictive accuracy, and ensure fairer decision-making.

---

## Project Overview

Financial institutions traditionally rely on manual evaluation for loan approvals, which is time-consuming and prone to human bias.  
This project automates the loan approval process using **machine learning techniques**, enhancing efficiency, accuracy, and fairness.

Key objectives:

- Automate the loan approval workflow.
- Optimise predictive performance via **hyperparameter tuning**.
- Improve interpretability using **LIME** for explainable AI.
- Ensure balanced decision-making by addressing **class imbalance**.

---

## Models Implemented

- **Random Forest** – Tuned using GridSearchCV.
- **XGBoost** – Optimised for improved performance.
- **Stacking Ensemble** – Combines Random Forest and XGBoost with a **Logistic Regression meta-learner**.
- **Voting Ensemble** – Soft voting combining tuned Random Forest and XGBoost.

---

## Evaluation Metrics

We evaluated performance using:

- **Accuracy** – Overall correctness.
- **Precision & Recall** – For class-specific performance.
- **F1 Score** – Balance between precision and recall.
- **ROC-AUC** – Discrimination ability.

---

## Results

Best Model: Tuned Random Forest

F1 Score: 87%

ROC-AUC: 90%

## Future Work

- Explore advanced **deep learning techniques** such as neural networks and transformer-based models to improve classification performance.
- Allocate more time for **hyperparameter fine-tuning** and experiment with **advanced ensemble methods**, including gradient blending and neural meta-learners.
- Integrate richer **financial features** like credit history, banking transactions, and macroeconomic indicators to enhance predictive power.
- Expand model **explainability** by incorporating **SHAP** alongside LIME for both local and global interpretation of predictions.
- Deploy the model in a **real-time environment**, such as a **web-based loan screening tool** or **decision support dashboard**, to demonstrate practical applicability.
