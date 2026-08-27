# 🌾 Smart Agricultural AI Systems (NTI & ITIDA Summer Training)

An end-to-end Machine Learning project suite designed to revolutionize agriculture through smart crop recommendation and harvest yield prediction. Developed as part of the **NTI & ITIDA Summer Training**.

---

## 👨‍💻 Project Team
* **Huthyfa Moamen Marei**
* **Mohamed Alaaeldin Ragab Allam**
* **Serag elden Mohamed Samir Ahmed**

---

## 🚀 Live Web Applications

Explore our deployed interactive machine learning web applications:

* **🌱 Smart Crop Recommendation System (Classification):** [Open Crop Recommender App](https://crop-recommendation-system-fqeph5sec9kmxqmzzpzzf8.streamlit.app/)
* **📈 Smart Crop Yield Predictor (Regression):** [Open Crop Yield Predictor App](https://regression-nvdkdspv3ewsi7cvst6kbf.streamlit.app/)

---

## 📌 Project Overview & Architecture

Modern agriculture requires data-driven decisions to maximize yield and optimize resource allocation. Our project is split into two independent, robust modules:

### 1. 🌱 Crop Recommendation Module (Classification)
* **Goal:** Recommends the optimal crop to cultivate based on environmental and soil conditions.
* **Input Parameters:** Nitrogen ($\text{N}$), Phosphorus ($\text{P}$), Potassium ($\text{K}$), Temperature, Humidity, pH, and Rainfall.
* **Algorithms Evaluated:** Decision Trees, Support Vector Machines (SVM), Random Forest, and **XGBoost**.
* **Best Performer:** **XGBoost Classifier** achieving **99.3% accuracy**.

### 2. 📈 Crop Yield Prediction Module (Regression)
* **Goal:** Forecasts the expected harvest yield ($\text{hg/ha}$) for various crop items across different regions.
* **Input Parameters:** Year, Average Rainfall ($\text{mm/year}$), Pesticides ($\text{tonnes}$), Average Temperature ($\text{°C}$), Crop Type, and Area Encoding.
* **Algorithm:** **XGBoost Regressor** optimized for multi-feature agricultural regression.

---

## 📊 Model Performance Summary

| System Type | Model / Algorithm | Performance Metric |
| :--- | :--- | :--- |
| **Crop Recommendation** | XGBoost Classifier | **99.3% Accuracy** 🏆 |
| **Yield Prediction** | XGBoost Regressor | **High $R^2$ Score & Minimal RMSE** 🏆 |

---

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python
* **Machine Learning & Data Processing:** Pandas, NumPy, Scikit-Learn, XGBoost, Joblib
* **Web Framework:** Streamlit
* **Deployment & Version Control:** Streamlit Cloud & GitHub

---

## 📂 Project Structure
```text
├── app.py                     # Main Streamlit application
├── crop_model.pkl             # Trained XGBoost classification model
├── label_encoder.pkl          # Label encoder for crops
├── yield_model.pkl            # Trained XGBoost regression model
├── requirements.txt           # Required dependencies
└── README.md                  # Comprehensive project documentation
