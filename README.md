[README.md](https://github.com/user-attachments/files/27009006/README.md)
# 💼 Employee Salary Prediction Web App

A machine learning web application that predicts employee salaries based on key factors like experience, role, and department. Built end-to-end — from data analysis to a live, interactive web interface.

---

## 🚀 Live Demo

> Run locally using the steps below.

---

## 📌 Project Overview

This project was developed during my **AI & ML Internship at IBM / Edunet Foundation (AICTE)**. The goal was to build a complete ML pipeline that takes employee data as input and predicts the expected salary using a trained Linear Regression model.

---

## 🛠️ Tech Stack

| Layer | Tools |
|---|---|
| Language | Python |
| ML & Data | Scikit-learn, NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Web App | Streamlit |
| Model Serialization | Joblib |
| Notebook | Jupyter Notebook |
| Dataset | Excel (Employees.xlsx) |

---

## 📂 Project Structure

```
Employee-Salary-Prediction/
│
├── Analysis_Modelling.ipynb   # Data analysis, preprocessing & model training
├── app.py                     # Streamlit web application
├── Employees.xlsx             # Dataset
├── linearmodel.pkl            # Trained Linear Regression model
└── data.txt                   # Supporting data file
```

---

## ⚙️ How to Run Locally

**1. Clone the repository**
```bash
git clone https://github.com/routhujahnavi/Employee-Salary-Prediction-by-R.Jahnavi.git
cd Employee-Salary-Prediction-by-R.Jahnavi
```

**2. Install dependencies**
```bash
pip install streamlit scikit-learn pandas numpy joblib openpyxl
```

**3. Run the app**
```bash
streamlit run app.py
```

Then open `http://localhost:8501` in your browser.

---

## 🧠 ML Pipeline

1. **Data Loading** — Loaded employee dataset from Excel
2. **Exploratory Data Analysis** — Visualized distributions and correlations using Matplotlib & Seaborn
3. **Preprocessing** — Handled missing values, encoded categorical features, scaled numerical data
4. **Model Training** — Trained a Linear Regression model using Scikit-learn
5. **Evaluation** — Achieved **95% R-squared score** on test data
6. **Deployment** — Serialized model with Joblib and deployed via Streamlit

---

## 📊 Model Performance

| Metric | Score |
|---|---|
| R-squared (R²) | 95% |
| Algorithm | Linear Regression |

---

## 👩‍💻 Author

**R. Jahnavi Santoshi**
- GitHub: [@routhujahnavi](https://github.com/routhujahnavi)
- LinkedIn: [routhu-jahnavi-santoshi](https://linkedin.com/in/routhu-jahnavi-santoshi)
