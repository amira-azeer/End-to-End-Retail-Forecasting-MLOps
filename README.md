# End-to-End-Retail-Forecasting-MLOps
End-to-end machine learning project to forecast quarterly sales revenue for SuperKart, a multi-city retail chain. The solution leverages historical product and store data to build, tune, and deploy predictive models that support inventory optimization and regional sales strategy.

### 📌 Business Objective

Develop a scalable forecasting system that:

* Predicts product-store level sales revenue
* Supports inventory planning and supply chain decisions
* Enables data-driven regional sales strategies
* Integrates into business decision-making systems

---

## 📊 Project Workflow

### 1️⃣ Exploratory Data Analysis (EDA)

* Data shape, types, missing values, duplicates
* Univariate & bivariate analysis
* Key sales drivers identification
* Business insights extraction

### 2️⃣ Data Preprocessing

* Feature engineering
* Outlier detection & treatment
* Train-test split
* Categorical encoding via preprocessing pipeline

### 3️⃣ Model Building

Implemented and evaluated:

* 🌳 Random Forest
* ⚡ XGBoost

Metric Selection: *R² / RMSE (based on business relevance to revenue forecasting)*

### 4️⃣ Hyperparameter Tuning

* GridSearch / RandomizedSearch
* Performance optimization
* Tuned model comparison

### 5️⃣ Model Selection & Serialization

* Best model selected based on validation performance
* Final evaluation on test set
* Model serialized using `joblib`
* Loaded model used for inference

---

## 🚀 Deployment

### 🔹 Backend (Flask API)

* REST API for predictions
* Dockerized application
* Hosted on Hugging Face Spaces (Docker)

### 🔹 Frontend (Streamlit App)

* Interactive UI for revenue prediction
* Hosted on Hugging Face Spaces (Streamlit)

---

## 📦 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Flask
* Streamlit
* Docker
* Hugging Face Spaces

---

## 💡 Business Impact

* Improved demand planning
* Reduced inventory risk
* Optimized regional sales strategies
* Data-driven decision support across verticals

---
