# 🚢 Titanic Survival Prediction

A machine learning project based on the **Kaggle Titanic: Machine Learning from Disaster** competition.  
This project predicts passenger survival using data analysis, feature engineering, and classification models.

---

## 📘 Overview

This project demonstrates how data preprocessing, feature engineering, and model optimization can improve prediction accuracy on real-world datasets.

---

## 🧠 Model Used
| Model | Public Score | Description |
|:------|:-------------:|:------------|
| Random Forest Classifier | With advanced feature engineering (Title, FamilySize, IsAlone, AgeBin, FareBin) |

---
## ⚙️ Features Engineered
- **Title extraction** (Mr, Miss, Mrs, etc.)
- **FamilySize** and **IsAlone**
- **Age** and **Fare** binning
- **Embarked & Sex** encoding
- **Missing value imputation**

---

## 🧩 Workflow
1. Load and explore data  
2. Handle missing values  
3. Create new engineered features  
4. Encode categorical variables  
5. Train using Random Forest  
6. Optimize hyperparameters  
7. Submit predictions to Kaggle
