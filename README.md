# 📊 Telecom Customer Churn Prediction

## 🚀 Overview

Customer churn is a major revenue risk in the telecom industry. This project builds a machine learning model to identify customers likely to churn and support data-driven retention strategies.

---

## 🧠 Problem

Telecom companies lose customers due to pricing, service quality, and contract flexibility. The challenge is to predict which customers are at risk of leaving before it happens.

---

## ⚙️ Solution

* Built a Gradient Boosting model using Scikit-learn
* Performed feature engineering and preprocessing
* Handled class imbalance using SMOTE
* Tuned model using GridSearchCV

---

## 📈 Results

* ROC-AUC: 0.844
* Accuracy: 79%

### 🔍 Key Drivers of Churn (via SHAP)

* Contract type
* Fibre optic internet
* Monthly charges

---

## 📊 Model Performance

![ROC Curve](images/roc_curve.png)
![Confusion Matrix](images/confusion_matrix.png)
![SHAP Summary](images/shap_summary.png)

---

## 🔍 Key Insights

* Customers on month-to-month contracts have the highest churn risk
* Higher monthly charges correlate strongly with churn
* Fibre optic users show increased churn probability

These insights can guide targeted retention strategies.

---

## 🔄 ML Pipeline

1. Data preprocessing and cleaning
2. Feature engineering
3. Handling class imbalance (SMOTE)
4. Model selection and tuning
5. Model evaluation
6. Model interpretability using SHAP

---

## 🚀 Production Considerations

If deployed in a real-world system:

* Serve model using FastAPI
* Automate pipelines using Airflow
* Monitor model performance and drift
* Store data/models using AWS S3
* Visualize insights using Power BI dashboards

---

## 🛠 Tech Stack

Python, Pandas, NumPy, Scikit-learn, SHAP, SMOTE, Matplotlib

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies
   pip install -r requirements.txt
3. Run the notebook in the notebooks/ folder

---

## 📂 Project Structure

* data/ → dataset
* notebooks/ → analysis and modeling
* images/ → visualizations

---

## 📬 Contact

LinkedIn: https://linkedin.com/in/madhav-grover-a126b1226
Email: [grovermadhav@gmail.com](mailto:grovermadhav@gmail.com)
