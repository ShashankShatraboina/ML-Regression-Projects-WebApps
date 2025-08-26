# ML Regression Projects WebApp

This repository contains a **Streamlit web application** deployed on **Streamlit Cloud** that integrates **six regression-based machine learning projects**. Each project uses optimized ML models to deliver accurate predictions across different domains.

### Included Projects

* 🏠 House Price Prediction
* 🚗 Car Price Prediction
* 🪙 Gold Price Prediction
* 🏥 Medical Insurance Cost Prediction
* 🏬 Big Mart Sales Prediction
* 🔥 Calories Burnt Prediction

---

## 📌 Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Dataset Description](#dataset-description)
5. [Technologies Used](#technologies-used)
6. [Model Development Process](#model-development-process)
7. [Models Used](#models-used)
8. [Model Evaluation](#model-evaluation)
9. [Conclusion](#conclusion)
10. [Deployment](#deployment)
11. [Contributing](#contributing)
12. [Contact](#contact)

---

## 🔎 Overview

The web app provides an interactive interface where users can choose from six regression projects and input custom features to receive predictions. Each model is built through **data-driven feature engineering, model selection, and hyperparameter tuning**, ensuring both **accuracy** and **reliability**.

---

## ⚙️ Installation

Run the project locally by following these steps:

```bash
# Clone repository
git clone <repository_url>
cd <project_directory>

# Install dependencies
pip install -r requirements.txt
```

---

## ▶️ Usage

Launch the Streamlit application:

```bash
streamlit run streamlit_app.py
```

Once started, the app will open in your browser. Use the **sidebar** to select a regression project, enter feature values, and generate predictions.

---

## 📂 Dataset Description

### 🏠 House Price Prediction

Predicts property prices based on **location, size, bedrooms, and other attributes**.

### 🚗 Car Price Prediction

Estimates car resale prices from **brand, model, year, mileage, and engine specifications**.

### 🪙 Gold Price Prediction

Forecasts gold prices using **historical data, currency exchange rates, inflation, and financial indicators**.

### 🏥 Medical Insurance Cost Prediction

Predicts insurance premiums based on **age, BMI, smoking status, and health details**.

### 🏬 Big Mart Sales Prediction

Forecasts sales across stores depending on **item visibility, store type, and marketing data**.

### 🔥 Calories Burnt Prediction

Calculates calories burnt during physical activity using **age, weight, exercise duration, and activity type**.

---

## 🛠️ Technologies Used

* **Programming**: Python
* **Framework**: Streamlit
* **Machine Learning**: Scikit-learn, XGBoost
* **Data Analysis & Visualization**: Pandas, NumPy, Matplotlib, Seaborn

---

## 📊 Model Development Process

For each regression project, the following workflow was applied:

1. **Data Import & Dependencies**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preprocessing**

   * Handle missing values & outliers
   * Encode categorical variables
   * Feature scaling
4. **Model Selection**

   * Train multiple regression models
   * Evaluate via cross-validation
   * Select top 3 performing models
5. **Model Optimization**

   * Recursive Feature Elimination (RFE)
   * Hyperparameter tuning with GridSearchCV
   * Final model selection based on evaluation metrics

---

## 🤖 Models Used

**House Price Prediction**

* Linear Regression
* Random Forest Regressor
* XGBoost

**Car Price Prediction**

* Linear Regression
* Random Forest Regressor
* XGBoost

**Gold Price Prediction**

* K-Nearest Neighbors
* Random Forest Regressor
* XGBoost

**Medical Insurance Cost Prediction**

* K-Nearest Neighbors
* Random Forest Regressor
* XGBoost

**Big Mart Sales Prediction**

* Linear Regression
* Lasso Regression
* XGBoost

**Calories Burnt Prediction**

* K-Nearest Neighbors
* Random Forest Regressor
* XGBoost

---

## 📈 Model Evaluation (R² Scores)

| Project                         | Best Model              | R² Score |
| ------------------------------- | ----------------------- | -------- |
| 🏠 House Price Prediction       | Linear Regression / RF  | 0.9999+  |
| 🚗 Car Price Prediction         | Random Forest Regressor | 0.6681   |
| 🪙 Gold Price Prediction        | KNN                     | 0.9893   |
| 🏥 Medical Insurance Prediction | Random Forest Regressor | 0.8726   |
| 🏬 Big Mart Sales Prediction    | XGBoost                 | 0.6142   |
| 🔥 Calories Burnt Prediction    | XGBoost                 | 0.9993   |

---

## ✅ Conclusion

The **ML Regression Projects WebApp** provides an intuitive platform for predictive modeling across diverse domains. By combining multiple algorithms, fine-tuned features, and robust evaluation metrics, it ensures **practical and high-accuracy predictions**.

---

## 🚀 Deployment

The application is deployed on **Streamlit Cloud** and accessible here:
\[ML Regression Projects WebApp]

---

## 🤝 Contributing

Contributions are welcome! Please **open an issue** or **submit a pull request** with your ideas or improvements.

---

## 📬 Contact

For questions or suggestions, feel free to reach out:
📧 **[shashankshatraboina@gmail.com](mailto:shashankshatraboina@gmail.com)**

---
