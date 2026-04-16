# Enhancing Clinical Trust in Predictive Healthcare: An XAI Approach

This repository contains the dataset and Python code utilized in the IEEE conference paper: **"Enhancing Clinical Trust in Predictive Healthcare: An Explainable AI Approach Using SHAP and LIME."**

## Overview
The goal of this project is to demonstrate how high-performing, "black-box" machine learning models (like XGBoost) can be made interpretable for clinical settings. We utilize the Pima Indians Diabetes Database to predict disease onset and apply two Explainable AI (XAI) frameworks:
* **SHAP (SHapley Additive exPlanations):** Used for global feature importance to identify population-level risk factors.
* **LIME (Local Interpretable Model-agnostic Explanations):** Used to generate patient-specific narratives to build physician trust.

## Repository Contents
* `diabetes.csv`: The benchmark dataset used for training and evaluation.
* `XAI_Using_SHAP_Diabetes.ipynb`: The main script containing data preprocessing, model training (Logistic Regression, Random Forest, XGBoost), and XAI visualization generation.

## Results
The XGBoost model achieved an AUC of 0.79. The code successfully generates:
1. Confusion Matrices and ROC Curves for performance evaluation.
2. SHAP Summary Plots for global interpretability.
3. LIME feature weight visualizations for local interpretability.

## Requirements
To run this code locally, ensure you have the following Python libraries installed:
`pandas`, `numpy`, `scikit-learn`, `xgboost`, `shap`, `lime`, `matplotlib`
