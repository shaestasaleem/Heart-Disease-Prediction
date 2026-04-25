# 💓 Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project predicts the presence of heart disease in patients using machine learning techniques.
We apply multiple classification algorithms and compare their performance to identify the most accurate model.

## 🌐 Live App

🚀 **[Click here to open the Streamlit App] https://heart-disease-prediction-ad6ssbzfoudbjv2vpdxvvy.streamlit.app/**




## 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── heart.ipynb                          # Main Jupyter Notebook
├── app.py                               # Streamlit Web App
├── lr_model.pkl                         # Logistic Regression Model
├── rf_model.pkl                         # Random Forest Model
├── xgb_model.pkl                        # XGBoost Model (Best)
├── heart_disease_model.pkl              # Combined trained model
├── encoders.pkl                         # Label Encoders
├── columns.pkl                          # Feature Columns
├── heart_disease_uci.csv                # Dataset
├── requirements.txt                     # Dependencies
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
9. **Web App** — Deployed on Streamlit

---

## 🤖 Models Used

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 78.8% |
| Random Forest | 83.7% |
| XGBoost ✅ | 85.9% |

---

## 🏆 Best Model: XGBoost

XGBoost achieved the highest accuracy among all three models for binary classification (Heart Disease: Yes/No).

---

## 🛠️ Technologies Used

streamlit
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn
joblib
---

## 📊 Dataset

**Heart Disease UCI Dataset**
- 🔗 [Download Dataset from Kaggle](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-uci)
- Binary target: `1` = Heart Disease Present, `0` = Healthy
- Features include age, sex, chest pain type, blood pressure, cholesterol, and more

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```
   git clone https://github.com/shaestasaleem/Heart-Disease-Prediction.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```
   streamlit run app.py
   ```
4. Or open `heart.ipynb` in Jupyter Notebook and run all cells

---

*Submitted as ML Lab Project — DSAI Batch 2023*
