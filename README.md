<h1 align="center">🚀 End-to-End AI-Powered Retention System</h1>

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Made%20with-Python-blue?logo=python"></a>
  <a href="https://pandas.pydata.org/"><img src="https://img.shields.io/badge/Data-Pandas%20%7C%20NumPy-150458?logo=pandas"></a>
  <a href="https://scikit-learn.org/"><img src="https://img.shields.io/badge/Framework-Scikit--learn-orange?logo=scikitlearn"></a>
  <a href="https://xgboost.readthedocs.io/"><img src="https://img.shields.io/badge/Models-XGBoost%20%7C%20LightGBM-2b6cb0"></a>
  <a href="https://shap.readthedocs.io/"><img src="https://img.shields.io/badge/Explainability-SHAP-6f42c1"></a>
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

> 🧠 Predict customer churn at scale (1M rows) and enable retention strategies with a full, notebook-driven ML pipeline.

This project builds a production-style churn prediction workflow—from raw data loading and cleaning to feature engineering, model training, and explainability—using a large customer dataset.

## 🎯 Objective
Build a machine learning model that predicts customer churn and identifies the most influential drivers to support targeted retention campaigns.

## 📦 Dataset Overview
- **File:** customer_churn_1M.csv
- **Scaled:** ~1,000,000 rows, ~30 + columns
- **Target:** Churn (binary)
- **Source:** https://www.kaggle.com/datasets/isandeep06/customer-churn-prediction-dataset-1m

## 📊 Process Breakdown (Notebook.ipynb)

### Step 1. Data Loading & Profiling
- Load the dataset and verify shape, schema, and column types.
- Split columns into numerical and categorical groups.

### Step 2. Missing Value Treatment
- Compute missingness per column.
- Impute numerical with median and categorical with mode.

### Step 3. EDA (Exploratory Data Analysis)
- Distributions and outlier checks for numeric features.
- Category frequency and churn-rate analysis for categorical features.

### Step 4. Feature Engineering
- Clean column names and types.
- Binning, encoding, and optional missingness flags.

### Step 5. Modeling
- Train baseline and advanced models.
- Handle class imbalance (where needed) with imbalanced-learn.
- Evaluate with accuracy, F1, ROC-AUC, and confusion matrix.

### Step 6. Explainability
- Use SHAP to interpret global and local feature impact.

## 🔧 Technologies & Libraries Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost & LightGBM
- imbalanced-learn
- SHAP

## 📁 Project Structure

```
📦 End-to-End AI-Powered Retention System
├── customer_churn_1M.csv
├── End-to-End AI-Powered Retention System.txt
├── Notebook.ipynb
├── churn_model_artifact.pkl
├── requirements.txt
└── README.md
```

## 🚧 Ongoing Work
- Add production-grade feature store for reusable transformations.
- Build a lightweight inference API for churn scoring.
- Create automated data validation checks before training.
- Improve model monitoring and drift detection.

## 👨‍💻 Author
**Sandeep Maurya**

📧 [isandeeep06@gmail.com](mailto:isandeeep06@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/sandeepmaurya-datascientist)  
🌐 [Portfolio](https://isandeep06.github.io/)

---

## 🌟 Support
If this project helped you:

⭐ Star this repo  
📢 Share it with others  
💬 Open an issue for suggestions or improvements
