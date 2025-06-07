# 📈 Python Stocks Analysis & Price Range Predictor

This project compares and analyzes historical stock data of **Google** and **Apple**, applies feature engineering, and builds machine learning models to predict which stock exhibits the **highest daily price range**. It includes EDA, preprocessing pipelines, modeling, PCA, and MLflow logging — all stored and queried from an SQLite database.

---

## 🚀 Features

- 📊 Automated EDA using `ydata_profiling`
- 🧹 Data preprocessing with custom scikit-learn pipelines
- 🗃️ SQLite database creation and SQL joins for merging Apple & Google stock data
- 🔍 Feature engineering to derive daily price changes
- 🌈 Visualization with Seaborn and Matplotlib
- 🧠 Model training using:
  - `RandomForestRegressor` (via pipeline)
  - `QDA`, `LDA`, and `CalibratedClassifierCV` with `GridSearchCV`
- ⚙️ Dimensionality reduction with PCA
- 📦 Model saving using `dill`
- 📈 Experiment tracking via MLflow and DagsHub

---
Created By
Wanshika Patro
Samidha Bhosale
Ashutosh Panigrahi
