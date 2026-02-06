# 📈 Linear Regression — Ecommerce App vs Website Revenue Analysis

A supervised machine learning project that uses **Linear Regression** to analyze customer behavior data and predict yearly spending for an ecommerce company.

The goal is to determine whether the company should focus more on improving the **mobile app** or the **website experience** based on model insights.

---

## 📌 Overview

This project applies Linear Regression to model the relationship between customer activity metrics and yearly spending. After training the model, feature coefficients are analyzed to interpret which platform contributes more to revenue.

The workflow includes exploratory analysis, visualization, model training, and coefficient interpretation.

---

## 🎯 Objective

Predict:
`Yearly Amount Spent`

Using features such as:

- Avg session length
- Time on app
- Time on website
- Length of membership

And use model coefficients to guide business decisions.

---

## 🧠 Learning Type

**Supervised Learning — Regression**

- Continuous target prediction
- Linear relationship modeling
- Coefficient interpretation

---

## 🧩 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset

Ecommerce customer dataset containing usage and membership metrics.

Target variable:

`Yearly Amount Spent`

---

## 🔬 Project Workflow

### 1️⃣ Exploratory Data Analysis
- Pair plots
- Correlation checks
- Feature vs target visualization
- Trend identification

---

### 2️⃣ Preprocessing
- Feature selection
- Train/test split
- Numeric feature validation

---

### 3️⃣ Model Training

Linear Regression model:

`sklearn.linear_model.LinearRegression`

Model fitted on training data and used to predict spending.

---

### 4️⃣ Evaluation

Model evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Residual analysis

---

### 5️⃣ Interpretation

- Coefficients analyzed
- Feature impact compared
- Business recommendation derived (App vs Website focus)

---

## 📈 Results
```
MAE: 7.2281486534308295
MSE: 79.81305165097444
RMSE: 8.933815066978633
```

Where MAE is mean absulute error, MSE is mean squared error, and RMSE is root mean squared error.

Observation: App usage showed stronger coefficient impact than website usage.

---

## ⚙️ Key Concepts Demonstrated

- Linear Regression
- Continuous value prediction
- Model coefficient interpretation
- Residual analysis
- Business insight from ML models
- Regression error metrics

---

## ▶️ How to Run

### Clone repository

```bash
git clone https://github.com/rohitb281/linear-regression-app_or_website.git
cd linear-regression-app_or_website
```

### Install dependencies
```
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Launch notebook
```
jupyter notebook
```

### Open:
```
Linear Regression Project.ipynb
```
- Run all cells.

---

## 🚀 Possible Improvements
- Add polynomial regression comparison
- Feature interaction terms
- Cross-validation
- Regularized regression (Ridge/Lasso)
- Model deployment as prediction API

----

## ⚠️ Limitations
- Assumes linear relationships
- Sensitive to outliers
- Requires feature independence

---

## 📄 License

Open for educational and portfolio use.

---

## 👤 Author

Rohit Bollapragada

GitHub: https://github.com/rohitb281
