# PlanWise: An Explainable AI for Multiclass Transportation Mode Prediction

## 📖 Overview
**PlanWise** is an explainable AI framework designed to recommend the most suitable transportation mode — **Cab, Family, or Bus** — based on contextual and personal preference features.  

The system integrates multiple machine learning classifiers (**Logistic Regression, Decision Tree, Random Forest, SVM, XGBoost**) with **SHAP (SHapley Additive exPlanations)** for interpretability. This ensures that predictions are not only accurate but also transparent and trustworthy.  

**Published on Zenodo:** [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16892087.svg)](https://doi.org/10.5281/zenodo.16892087)


---

## ✨ Features
- **Multiclass Classification** of transportation choices  
- **Explainable AI** using SHAP values and feature importance  
- **Evaluation Metrics:** Accuracy, F1 Score, ROC-AUC, Confusion Matrix  
- **Statistical Validation:** Paired T-tests and McNemar’s Test  
- **Visualization:** ROC curves, PR curves, PDP plots, SHAP plots  

---

## 🗂️ Dataset
The dataset includes:

**Numerical Features:**  
- Cost  
- Time Reliability  
- Safety Score  
- Comfort Level  
- Social Acceptability  
- Legal Risk  
- Travel Time  

**Categorical Features:**  
- Weather  
- Day Type  

**Target Variable:**  
- Best Option (Cab / Family / Bus)  

---

## 📊 Results

- Best Model: XGBoost achieved the highest ROC-AUC score and significantly outperformed Random Forest

- Key Features: Cost, Day Type, and Travel Time were most influential in predictions

- xplainability: SHAP plots provide per-instance transparency and feature interactions

---

## 👩‍💻 Author

- **Debaswini Moharana**
- **Independent Researcher | Machine Learning Intern**
- **Email: debaswinimoharana@gmail.com**

---

##  📖 Citation
If you use this work, please cite:

Moharana, D. (2025). *PlanWise: An Explainable AI for Multiclass Transportation Mode Prediction*. Zenodo. https://doi.org/10.5281/zenodo.16892087


---
