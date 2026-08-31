# Student Performance Prediction & Risk Assessment System

📊 **An end-to-end Machine Learning regression pipeline built to predict student academic scores and identify at-risk students using advanced ensemble algorithms.**

---

## 📌 Project Overview
Predicting student performance allows educational institutions to stage early interventions for students vulnerable to academic failure. This project develops a comprehensive machine learning regression pipeline that inputs demographic, social, and historic academic data to predict a student's final scores accurately. 

By utilizing a wide array of regression models—ranging from standard linear techniques to sophisticated boosting frameworks—this system optimizes predictive accuracy to serve as a reliable early-warning mechanism.

---

## ⚙️ Key Features
* **Multi-Model Benchmark Pipeline:** Evaluates 9 distinct machine learning algorithms simultaneously to find the absolute best predictive fit for educational data.
* **Automated Hyperparameter Optimization:** Implements `RandomizedSearchCV` to fine-tune model parameters and maximize generalization on unseen data.
* **Robust Evaluation Framework:** Evaluates models across three critical dimensions: Mean Absolute Error (MAE), Mean Squared Error (MSE), and the Coefficient of Determination (R² Score).
* **Statistical Visualization:** Uses Seaborn and Matplotlib to map feature correlations, error distributions, and residual variance plots.

---

## 🛠️ Architecture & Tech Stack

The architecture leverages a comprehensive ecosystem of modern machine learning tools:

* **Data Wrangling & Compute:** NumPy, Pandas
* **Data Visualization:** Seaborn, Matplotlib
* **Core ML Framework:** Scikit-Learn (sklearn)
* **Gradient Boosting:** CatBoost

### Implemented Algorithms:
* **Linear & Regularized:** Linear Regression, Ridge Regression, Lasso Regression
* **Distance & Support Vectors:** K-Neighbors Regressor (KNN), Support Vector Regressor (SVR)
* **Tree & Ensemble Methods:** Decision Tree Regressor, Random Forest Regressor, AdaBoost Regressor
* **Advanced Boosting:** CatBoost Regressor
