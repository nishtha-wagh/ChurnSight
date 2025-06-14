# ChurnSight (WORK IN PROGRESS)
Predict and Explain SaaS Customer Churn 

### 🎯 Problem
Churn is a major cost driver for subscription-based businesses. This project builds a lightweight ML solution to predict customer churn and explain the top drivers behind it.

---

### 💡 Goals
- Predict customer churn based on behavioral, contract, and payment data.
- Explain top drivers using SHAP for business-friendly insight.
- Deploy as an interactive dashboard or API.

---

### 🛠 Stack
- Python (Pandas, Scikit-learn)
- SHAP (Explainability)
- Streamlit (Dashboard)
- FastAPI (Optional API endpoint)

---

### 🧪 Modeling
- Logistic Regression, XGBoost
- SMOTE (if needed for class imbalance)
- Model Evaluation: AUC, Precision, Recall

---

### 📈 Output
- Ranked list of churn risks
- Top 3 factors per user
- Business recommendations: discount, engage, upsell
