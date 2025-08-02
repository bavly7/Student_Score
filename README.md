# 🎓 Student Score Prediction – Task 1

This repository contains two different approaches to solving the **Student Score Prediction** task using Python and machine learning. The objective is to predict students' exam scores based on various factors such as study hours, participation, and more.

---

## 📌 Task Description

- **Dataset**: Student Performance Factors (Kaggle)
- **Goal**: Predict students’ final exam scores
- **Instructions**:
  - Perform data cleaning and basic visualization
  - Split the dataset into training and testing sets
  - Train a linear regression model
  - Evaluate the model using proper metrics
  - Visualize predictions
  - Bonus: Try polynomial regression and experiment with different feature combinations

---

## 📁 Repository Contents

### ✅ 1. `student-scoring-learning-model.ipynb` (Overfitting – Learning Only)
- This notebook explores how a model can **learn perfectly** from the dataset when **target-related features are leaked** into training.
- Achieved **100% accuracy** using a learning-based model.
- However, this model is **overfitted** and **not realistic**, as it uses features that are derived from the target class, which would not be available in real scenarios.
- Purpose: **To demonstrate what the model can learn**, but not to be used in production.

### ✅ 2. `student-score-best-model.ipynb` (Practical Solution with Innovation)
- Followed the task instructions using **Linear Regression** and **Polynomial Regression**.
- Observed that the dataset has only ~400 rows, making regression models perform poorly due to limited data.
- Tried other regressors like **Random Forest** and **XGBoost**, with minor improvements.
- Attempted **SMOTE** to increase sample size artificially, but it was unsuitable for regression.
- Final solution: **Reframed the problem as a binary classification**:
  - Students scoring less than 10 are labeled as **"Failed"**
  - Others are labeled as **"Passed"**
- This classification approach gave **much better performance** and demonstrated an **innovative take** on the original task.

---

## ⚙️ Tools & Libraries Used

- Python
- Pandas
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost
---

## 📊 Covered Topics

- Data Cleaning
- Data Visualization
- Linear Regression
- Polynomial Regression
- Random Forest & XGBoost Regressors
- Classification
- Overfitting Demonstration
- Evaluation Metrics (MAE, R², Confusion Matrix, Accuracy)

---

## 💡 Key Learnings & Innovations

- **Understanding model overfitting** through intentional feature leakage
- **Using classification instead of regression** when the dataset is small and noisy
- Applying multiple regression and classification techniques and evaluating their effectiveness
- Demonstrating critical thinking and innovation beyond task instructions

---

## 📬 Contact

bavly.waleed777@gmail.com  /  +20 1200020385   /  www.linkedin.com/in/bavly-waleed

Feel free to reach out for any clarifications or feedback. This work is intended for educational purposes and to showcase both learning and innovative thinking.

