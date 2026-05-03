# 🚢 Titanic Survival Prediction

A machine learning project based on the **Kaggle Titanic: Machine Learning from Disaster** competition.
This project predicts passenger survival using data analysis, feature engineering, and classification models, implemented in a Jupyter Notebook.

---

## 📘 Overview

This project demonstrates how exploratory data analysis (EDA), data preprocessing, feature engineering, and model building can improve prediction accuracy on real-world datasets.

---

## 📊 Exploratory Data Analysis (EDA)

* Analyzed survival distribution
* Visualized survival vs **Gender**, **Pclass**, and **Age**
* Checked missing values in dataset
* Used plots like:

  * Count plots
  * Histograms
  * Heatmap for correlation

---

## 🧹 Data Preprocessing

* Handled missing values:

  * **Age** → filled with median
  * **Embarked** → filled with mode
  * **Fare** → filled with median
* Converted categorical data:

  * **Sex**, **Embarked** → encoded
* Removed unnecessary columns:

  * Name, Ticket, Cabin

---

## ⚙️ Features Engineered

* **FamilySize** and **IsAlone**
* **Age** and **Fare** binning
* **Categorical encoding**
* **Missing value imputation**

---

## 🧠 Model Used

| Model                    | Description                                             |
| :----------------------- | :------------------------------------------------------ |
| Decision Tree Classifier | Used for classification with feature-engineered dataset |

---

## 🧩 Workflow

1. Load and explore data
2. Perform EDA (visualization & insights)
3. Handle missing values
4. Create new engineered features
5. Encode categorical variables
6. Train model using Decision Tree
7. Evaluate model performance
8. Generate predictions for test data
9. Submit results to Kaggle

---

## 💻 Tools & Technologies

* Python
* Jupyter Notebook
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 📈 Results

* Model: Decision Tree Classifier
* Accuracy: ~75–85% (depending on tuning)

---

## 📌 Conclusion

This project highlights how proper data analysis and preprocessing significantly impact machine learning model performance, even with simple models like Decision Tree.
