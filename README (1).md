# 💓 Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project predicts the presence of heart disease in patients using machine learning techniques.
We apply multiple classification algorithms and compare their performance to identify the most accurate model.

## 👥 Group Members

**Group # 3**

| Name | Roll Number |
|------|-------------|
| Savaira Majeed | DSAI231103031 |
| Shaesta Saleem | DSAI231103043 |
| Mustajab Zahra | DSAI231103016 |
| Faizan Nazik | DSAI231103023 |
| Sarfraz Ahmad | DSAI231103048 |
| Muhammad Gulfam | DSAI231103047 |

**Instructor:** Ms. Allah Rakhi Saman

---

## 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── heart.ipynb                          # Main Jupyter Notebook
├── heart_disease_model.pkl              # Saved trained model (XGBoost)
├── HeartDiseasePrediction_ML ppt.pdf   # Project Presentation
└── README.md                            # Project Documentation
```

---

## 🔬 Steps Performed

1. **Import Libraries** — pandas, numpy, sklearn, seaborn, matplotlib, xgboost
2. **Load Dataset** — Heart Disease UCI Dataset
3. **Data Exploration** — Visualizations (target distribution, age, gender, correlation heatmap)
4. **Data Cleaning** — Missing values handled using median/mode
5. **Encoding & Train-Test Split** — LabelEncoder, 80/20 split
6. **Model Training** — Three models trained and compared
7. **Model Evaluation** — Confusion Matrix + Classification Report
8. **Save Model** — Best model saved as `.pkl` file

---

## 🤖 Models Used

| Model | Description |
|-------|-------------|
| Logistic Regression | Baseline linear model |
| Random Forest | Ensemble tree-based model |
| XGBoost ✅ | Best performing model |

---

## 🏆 Best Model: XGBoost

XGBoost achieved the highest accuracy among all three models for binary classification (Heart Disease: Yes/No).

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- pandas, numpy
- scikit-learn
- XGBoost
- matplotlib, seaborn
- joblib

---

## 📊 Dataset

**Heart Disease UCI Dataset**
- 🔗 [Download Dataset from Kaggle](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-uci)
- Binary target: `1` = Heart Disease Present, `0` = Healthy
- Features include age, sex, chest pain type, blood pressure, cholesterol, and more

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:
   ```
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn joblib
   ```
3. Open `heart.ipynb` in Jupyter Notebook
4. Run all cells

---

*Submitted as ML Lab Project — DSAI Batch 2023*
