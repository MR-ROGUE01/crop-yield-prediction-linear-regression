<div align="center">

# 🌾 Crop Yield Prediction Using Machine Learning

### 🚜 Predicting Agricultural Productivity with Data-Driven Intelligence

<img src="https://img.shields.io/badge/Machine%20Learning-Regression-blueviolet?style=for-the-badge" />
<img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn" />
<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/R²%20Score-0.8815-brightgreen?style=for-the-badge" />

</div>

---

# 📖 Project Overview

Agriculture is heavily influenced by environmental and farming conditions. This project uses Machine Learning to predict crop yield (tons/hectare) based on factors such as rainfall, temperature, soil type, crop type, irrigation, fertilizer usage, and weather conditions.

The project demonstrates a complete end-to-end Machine Learning workflow including:

✅ Data Cleaning

✅ Exploratory Data Analysis

✅ Feature Engineering

✅ Model Training

✅ Hyperparameter Tuning

✅ Model Evaluation

✅ Pipeline Creation

✅ Model Serialization

---

# 🎯 Problem Statement

Predict:

```text
Yield_tons_per_hectare
```

using historical agricultural data.

### Input Features

| Feature        | Description             |
| -------------- | ----------------------- |
| 🌍 Region      | Geographical location   |
| 🌱 Soil Type   | Soil category           |
| 🌾 Crop        | Crop grown              |
| 🌧 Rainfall    | Rainfall received       |
| 🌡 Temperature | Temperature             |
| 🧪 Fertilizer  | Fertilizer usage        |
| 💧 Irrigation  | Irrigation availability |
| ☁ Weather      | Weather condition       |
| ⏳ Harvest Days | Days to harvest         |

---

# ⚙️ Machine Learning Workflow

```mermaid
flowchart LR

A[Dataset] --> B[Data Cleaning]
B --> C[EDA]
C --> D[Feature Engineering]
D --> E[Train Test Split]
E --> F[Model Training]
F --> G[Hyperparameter Tuning]
G --> H[Evaluation]
H --> I[Pipeline Creation]
I --> J[Model Serialization]
```

---

# 📊 Models Evaluated

| Model                | Train R² | Test R² |
| -------------------- | -------- | ------- |
| 🔵 Linear Regression | 0.8869   | 0.8815  |
| 🟣 Ridge Regression  | 0.8869   | 0.8815  |
| 🟠 Lasso Regression  | 0.8866   | 0.8816  |
| 🌳 Decision Tree     | 0.8759   | 0.8607  |
| 🌲 Random Forest     | 0.9313   | 0.8744  |

---

# 🏆 Final Selected Model

## Linear Regression

### Why Linear Regression?

✔ Best Generalization

✔ Very Small Train-Test Gap

✔ Easy Interpretability

✔ Stable Performance

✔ No Significant Overfitting

---

# 📈 Model Performance

<div align="center">

| Metric      | Value  |
| ----------- | ------ |
| 🎯 Train R² | 0.8869 |
| 🚀 Test R²  | 0.8815 |

</div>

---

# 🔥 Key Insights

### 🌧 Rainfall

Strong impact on agricultural productivity.

### 🌡 Temperature

Directly affects crop growth and development.

### 💧 Irrigation

Improves consistency in crop production.

### 🧪 Fertilizer

Positively contributes to higher yields.

### 🌍 Region

Different regions show varying productivity patterns.

---

# 🛠 Tech Stack

```text
Python
Pandas
NumPy
Matplotlib
Scikit-Learn
Joblib
Jupyter Notebook
```

---

# 📂 Repository Structure

```text
crop-yield-prediction-linear-regression/
│
├── data/
│   ├── crop_yield.csv
│   └── crop_yield_cleaned_sample.csv
│
├── notebooks/
│   ├── Week1_Data_Cleaning.ipynb
│   ├── Week2_EDA.ipynb
│   ├── Week3_Modeling.ipynb
│   └── Week4_Evaluation.ipynb
│
├── models/
│   ├── Pipeline.ipynb
│   └── crop_yield_pipeline.pkl
│
├── requirements.txt
└── README.md
```

---

# 🚀 Future Scope

* 🌐 Streamlit Deployment
* ☁ Weather API Integration
* ⚡ XGBoost
* 🔥 CatBoost
* 📊 Interactive Dashboard
* 🌍 Real Agricultural Dataset
* 📱 Farmer-Friendly Mobile App

---

# 🎓 Learning Outcomes

This project helped me gain practical experience in:

* Data Preprocessing
* Feature Engineering
* Regression Algorithms
* Hyperparameter Tuning
* Model Evaluation
* Pipeline Creation
* Model Deployment Preparation

---

<div align="center">

# 👨‍💻 Author

### Raj Kumar

🎓 B.Tech CSE (AI & ML)

🏫 Amity University Jharkhand

💡 Building AI & Machine Learning Projects

⭐ Star this repository if you found it useful!

</div>
