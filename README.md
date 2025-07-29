# Valuation_Velocity_Tracking_the_Explosive_Growth_of_Unicorn_Startups
# 🦄 Unicorn Valuation Prediction using CatBoost & SHAP

This project leverages machine learning—specifically the **CatBoost Regressor**—to predict the valuations of unicorn startups using key business features. SHAP (SHapley Additive exPlanations) is also used to interpret model predictions and understand feature influence.

---

## 🎯 Objective

To build a predictive model that can estimate a unicorn company’s valuation based on financial and categorical factors, and to understand what drives those predictions using SHAP explainability tools.

---

## 📊 Key Features

- Uses **CatBoost**, a gradient boosting algorithm optimized for categorical data.
- Evaluates model with **RMSE**, **R² Score**.
- SHAP analysis for feature importance & interpretability.
- Handles categorical encoding efficiently with minimal preprocessing.

---

## 🔍 Techniques Used

- CatBoost Regressor
- SHAP for model explainability
- Train/Test Split
- RMSE & R² scoring
- Feature engineering (e.g. handling 'Select Investors', 'Country', etc.)

---

## 🧠 SHAP Analysis Insights

- SHAP summary plots reveal top features influencing unicorn valuation predictions.
- This helps stakeholders understand **why** the model makes certain predictions.

> 🔬 Example insight: Companies from USA, with higher number of investors, and in specific sectors had the most influence on valuation.

---

## ⚙️ Requirements

```text
pandas
numpy
catboost
scikit-learn
matplotlib
shap

```
