DEMO LINK: https://medical-insurance-model-jxhg.onrender.com


# 🏥 Medical Insurance Cost Prediction 💸

This project uses a machine learning model to **predict the medical insurance charges** for individuals based on various personal attributes such as age, BMI, smoking status, and more.

The dataset was taken from **Kaggle** and is commonly used to learn regression modeling and data analysis techniques.

---

## 📁 Project Overview

### ✅ Goal
To accurately predict medical insurance charges using regression techniques after proper data understanding, preprocessing, and model evaluation.

### 📊 Dataset Features

- `age` — Age of the individual  
- `sex` — Gender (male/female)  
- `bmi` — Body Mass Index  
- `children` — Number of children  
- `smoker` — Smoking status (yes/no)  
- `region` — Residential region (northeast, southeast, etc.)  
- `charges` — **Target variable** (insurance cost)

---

## 🔍 Key Highlights

### 🧹 1. Data Preprocessing
- Checked for missing/null values
- Converted categorical features using `OneHotEncoding`
- Scaled numerical features where necessary
- Performed EDA using:
  - `seaborn` (heatmaps, pair plots)
  - `matplotlib` (distributions, histograms)
  - Correlation matrix to identify impactful features

### 🤖 2. Model Training & Selection
- Applied multiple regression models:
  - **Linear Regression**
  - **Decision Tree Regressor**
  - **Random Forest Regressor**
  - **Gradient Boosting Regressor**
- Tuned hyperparameters using `GridSearchCV`

### 📈 3. Evaluation Metrics
- R² Score
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

### 🧠 Final Outcome
The **Gradient Boosting Regressor** provided the best performance after hyperparameter tuning.

---

## 📚 Tech Stack

- Python 🐍
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn
- joblib / pickle (for model saving)

---

## 🚀 How to Run

1. Clone the repo  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
