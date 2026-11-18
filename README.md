# Construction Activity Delay Prediction & Decision Support System

An AI-driven decision-support web application for predicting construction activity delay risk before physical execution begins, featuring SHAP explainability and targeted mitigation recommendations.

## Overview
* **Model**: Random Forest Classifier (763 features) trained on 444,156 construction activities across 299 projects.
* **Explainability**: SHAP TreeExplainer for individual positive and negative factor contributions.
* **Interface**: Interactive Streamlit Dashboard with preloaded historical activities and custom activity simulation.

## Deployment on Render
* **Build Command**: `pip install -r requirements.txt`
* **Start Command**: `streamlit run app.py --server.port $PORT --server.address 0.0.0.0`
