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
| Random Forest Classifier | **0.76555** | With advanced feature engineering (Title, FamilySize, IsAlone, AgeBin, FareBin) |

---

## 📊 Visual Insights

Below are the key visualizations showcasing the correlation, feature importance, and relationships across variables used in the model:

![Titanic Data Visuals](titanic_analysis_overview.png)

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

---

## 📂 Files
| File | Description |
|:------|:-------------|
| `titanic_model.ipynb` | Main notebook |
| `titanic_submission_highscore.csv` | Final Kaggle submission (0.76555) |
| `titanic_preds_debug.csv` | Model prediction debug output |
| `train.csv`, `test.csv` | Original Kaggle data (not included here) |

---

## 💡 Results
- Achieved **0.76555 public leaderboard score**
- Improved from baseline (0.73684 → 0.76555)
- Demonstrated strong feature engineering and parameter tuning

---

## 👨‍💻 Author
**Muhammad Rayan Shahid**  
AI/ML Engineer | Kaggle Competitor  
🌐 [GitHub](https://github.com/muhammadrayans) • [LinkedIn](https://linkedin.com/in/muhammadrayanshahid) • [Kaggle](https://www.kaggle.com/muhammadrayans) • [YouTube](https://www.youtube.com/@ByteBrillianceAI)

---

## 🏆 Acknowledgements
Competition hosted by [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic).
