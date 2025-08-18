[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16892087.svg)](https://doi.org/10.5281/zenodo.16892087)



# PlanWise – Explainable AI for Multi-Class Transportation Mode Prediction  

🚖👨‍👩‍👧‍👦🚌  

This repository contains the implementation and documentation for **PlanWise**, an **Explainable AI (XAI) framework** that predicts transportation modes (Cab, Family, Bus) using machine learning classifiers. The framework integrates **SHAP** for transparent and interpretable predictions.  

---

## 📌 Overview  
Transportation mode choice impacts **time, cost, convenience, and sustainability**.  
PlanWise helps users make **informed commute decisions** by:  
- Predicting the **most suitable transportation mode**.  
- Explaining **why** a particular mode was suggested.  
- Comparing classifiers for performance and interpretability.  

---

## 🚀 Features  
- Multi-class classification (Cab, Family, Bus).  
- Machine learning models: Logistic Regression, Decision Tree, SVM, Random Forest,and XGBoost.  
- Model evaluation with accuracy, precision, recall, F1-score.  
- Explainability using **SHAP (SHapley Additive exPlanations)**.  
- Statistical validation with **McNemar’s Test** and **Paired T-Test**.  

---

## 📊 Dataset  
- Includes features such as **Cost,Time Reliability,
Safety Score,Comfort Level,Social Acceptability,
Legal Risk,Travel Time,Weather,Day Type,Best Option**.  
- Each sample is labeled with one of the three transportation modes: **Cab,Bus,Family**  
- Preprocessing includes encoding categorical variables and scaling numeric features.  

---

##  🔍 Tools used

- Python 
- Pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- shap

---

## ⚙️ Methodology  
1. **Data Preprocessing** → Encoding + Normalization.  
2. **Model Training** → Logistic Regression, Decision Tree, SVM, Random Forest, XGBoost.  
3. **Model Evaluation** → Accuracy, Precision, Recall, F1-score.  
4. **Explainability** → SHAP global + local interpretations.  
5. **Statistical Testing** → McNemar’s Test + Paired T-Test for validation.  

---

## 📈 Results (Highlights)  
- The model Decision tree and XGBoost  performed best.  
- SHAP revealed  **cost, day type and Travel time** as the key features.  
- Predictions are both **accurate** and **interpretable**.  

---

## 🔮 Future Work  
- Integration of Real-World Data: Future studies
could leverage large-scale mobility datasets(e.g.,GPS
traces,ride-hailing data, and public transport logs) to
validate and strengthen the model’s generalizability. 
- Inclusion of Additional Contextual Features: Ex-
panding feature sets to include traffic congestion,fuel
costs,dynamic pricing, and socio-demographic attributes
may provide deeper insights into travel behavior.
-Advanced Modeling Approaches: Investigating deep
learning models could capture temporal and spatial
dependencies in travel choices more effectively while
balancing explainability.
- Multi-Object Decision Support: Incorporating sustain-
ability measures such as carbon emissions into the
decision-making framework could support greener trans-
port planning.
- User-Centric Interfaces: Future Applications could
translate SHAP-based explanations into user-facing de-
cision aids, allowing commuters to make informed travel
choices aligned with their preferences and constraints.  

---

## 👩‍💻Author
**Debaswini Moharana**

---

