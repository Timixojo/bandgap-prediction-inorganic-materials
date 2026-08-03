# Bandgap Prediction for Inorganic Materials

A supervised machine learning project that predicts the bandgap energy of inorganic ABX₃ perovskite materials using multiple regression models.

## Overview

This project investigates the prediction of bandgap energy in inorganic ABX₃ perovskite materials using supervised machine learning techniques. Multiple regression models were developed, trained, and evaluated to identify the most effective approach for bandgap prediction.

## Objectives

- Predict bandgap energy using supervised machine learning.
- Compare the performance of multiple regression models.
- Identify the most accurate predictive model.

## Dataset

This project uses the **ML_abx3_dataset**, a publicly available dataset developed for target property prediction and classification using machine learning.

- **Dataset:** ML_abx3_dataset
- **Source:** Ericsson Tetteh Chenebuah & David Tetteh Chenebuah (2023)
- **DOI:** https://doi.org/10.48550/arXiv.2312.11335
- **Domain:** Inorganic ABX₃ Perovskite Materials
- **Target Variable:** Bandgap Energy

The dataset used in this project is included in the `data` directory.

## Models

The following supervised regression models were developed and evaluated:

- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regression (SVR)
- XGBoost Regressor

## Documentation

For the complete research methodology, implementation details, experimental results, discussion, and references, see:

- 📄 `docs/bandgap_prediction_report.pdf`
- 📊 `docs/presentation.pptx`
