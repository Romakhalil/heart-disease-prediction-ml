## ❤️ Heart Disease Prediction using Machine Learning and Explainable AI

This project develops machine learning models to predict the risk of heart disease using demographic, lifestyle, and clinical variables. The focus is on improving sensitivity, model interpretability, and supporting data-driven healthcare decision making.

This was completed as a **group project** as part of the Master’s in Data Science program at Berlin University of Applied Sciences and Technology (BHT).

---

## 📌 Motivation

Cardiovascular diseases remain one of the leading causes of mortality worldwide. Early risk prediction can support preventive care, reduce healthcare burden, and improve clinical outcomes. This project explores predictive modelling and explainable AI methods to identify high-risk individuals and provide interpretable insights.

---

## ⚙️ Project Workflow

The project follows a complete machine learning pipeline:

1. Data preprocessing and cleaning
2. Exploratory data analysis and feature understanding
3. Handling class imbalance
4. Model training and validation
5. Threshold tuning to improve sensitivity
6. Model evaluation and comparison
7. Explainable AI and model interpretation

---

## 🧰 Tools and Technologies

* R
* Random Forest
* Naive Bayes
* caret
* Explainable AI (DALEX)
* Statistical modelling
* Data visualization

---
## 🚀 Installation  

Install the required R packages:

```r
install.packages(c("caret", "randomForest", "e1071", "pROC", "DALEX", "dplyr", "ggplot2", "readr"))

## 📊 Results

The models demonstrated effective classification performance. Special emphasis was placed on sensitivity and recall to reduce false negatives, which is critical in healthcare applications.

Explainability techniques were used to understand key predictors and ensure transparency in model decisions.

### Confusion Matrix

Model performance was evaluated using confusion matrices for Random Forest and Naive Bayes.

### Feature Importance

The most important clinical and demographic predictors influencing heart disease risk were identified.

### Partial Dependence Analysis

Partial dependence profiles were used to explore how specific features influence predictions.

See the figures folder for visual results.

---

## 🌍 Applications

* Healthcare analytics
* Clinical decision support
* Preventive medicine
* Risk modelling and patient screening

---

## 📂 Data

The project uses a public heart disease dataset similar to the UCI Heart Disease dataset. The dataset includes demographic, clinical, and lifestyle variables relevant to cardiovascular risk.

---

## 🤝 Collaboration

This project was developed collaboratively as part of a group assignment. Responsibilities included data preprocessing, modelling, evaluation, and interpretation.

---

## 📂 Repository Structure

```
heart-disease-prediction-ml
│
├── figures
├── data
├── notebooks
├── README.md
```

---
## 🔑 Key Insights  

- Sensitivity is critical in healthcare prediction to avoid false negatives.  
- Lifestyle and clinical variables strongly influence heart disease risk.  
- Explainable AI improves transparency and trust in clinical decision support systems.

## 👩‍💻 Author

Roma Khalil Bhurgri
Master’s Student in Data Science
Berlin University of Applied Sciences and Technology (BHT)

---


