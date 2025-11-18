# 🕵️‍♀️ Credit Card Fraud Detection Using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning. It uses a highly imbalanced Kaggle dataset and applies data preprocessing, visualization, and model training techniques to identify suspicious transactions effectively.

---

## 📌 Project Objective

To build a machine learning model that can accurately classify transactions as **fraud** or **non-fraud**, helping financial institutions minimize losses by identifying suspicious activity.

---

## 📁 Dataset Information

- **Source:** Kaggle – Credit Card Fraud Dataset  
- **Total Transactions:** 284,807  
- **Classes:**  
  - `0` → Non-fraud  
  - `1` → Fraud  
- **Features:**  
  - V1–V28 (PCA-transformed)  
  - Time  
  - Amount  

⚠ **Dataset is NOT included in this repository** due to size and licensing.  
You can download it here: *Search "Kaggle Credit Card Fraud Dataset"*.

---

## 🧹 Steps Performed in the Notebook

### 1️⃣ Data Exploration & Preprocessing  
- Loaded the dataset  
- Checked missing values  
- Analyzed imbalance  
- Scaled features using `StandardScaler`  
- Split data into train/test

### 2️⃣ Models Trained  
#### ✔ Logistic Regression  
#### ✔ Random Forest Classifier  

### 3️⃣ Evaluation Metrics

| Model | Accuracy | Precision (Fraud) | Recall (Fraud) | F1-score (Fraud) |
|-------|----------|-------------------|-----------------|------------------|
| Logistic Regression | 0.9991 | 0.86 | 0.58 | 0.70 |
| Random Forest | 0.9995 | 0.95 | 0.79 | 0.86 |

👉 **Random Forest performed best overall.**

---

## 🧠 Conclusion

The Random Forest model provides a strong balance of accuracy and fraud detection capability.  
It can be used by banks & payment systems to flag high-risk transactions.

---

## 🛠 Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Joblib  

---

## 🚀 Future Improvements

- Use **SMOTE** to handle class imbalance  
- Try **advanced models** (XGBoost, LightGBM)  
- Build a **Flask/Streamlit deployment**  
- Add dashboards for visualization  

---

## 📂 Repository Structure

Credit-Card-Fraud-Detection/
│
├── 01_exploration_and_preprocessing.ipynb   # Main notebook
├── .gitattributes
└── README.md                                # Project documentation


---

## 🙋‍♀️ Author  
**Alishiba Ghatage**  
GitHub: github.com/alishibaghatage



