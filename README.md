# 🏦 Loan Approval Prediction App

This project is a **Machine Learning-based web app** built using **Streamlit** to predict whether a loan will be approved based on applicant details. The model is trained using a cleaned version of the [Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset).

---

## 📌 Features

- Predicts loan approval status using user input.
- Trained using **Random Forest Classifier** (best performer).
- Interactive UI using **Streamlit**.
- Cleaned and preprocessed data with encoding, log transformations, and handling of missing/imbalanced data.

---

## 🧠 Machine Learning Workflow

- **Data Preprocessing**:  
  - Missing value handling  
  - Encoding categorical variables  
  - Log transformation for skewed data  
  - Feature engineering (e.g., total income)

- **Model Used**:  
  `RandomForestClassifier` (best accuracy)

- **Model Evaluation**:  
  Evaluated using accuracy and confusion matrix on test set.

---

## 🛠 Technologies Used

- Python
- pandas, numpy
- scikit-learn
- imbalanced-learn
- matplotlib, seaborn
- joblib
- Streamlit

---

## 💡 How to Run

### ▶️ 1. Clone the repo / Download the files

bash
git clone https://github.com/your-username/loan-approval-prediction.git
cd loan-approval-prediction

pip install -r requirements.txt


streamlit run app.py

