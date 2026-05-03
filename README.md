# 📊 Customer Churn Analysis & Prediction

🚀 A data-driven project to analyze customer behavior, predict churn, and generate actionable insights for improving customer retention.

---

## 🎯 Project Objective

The goal of this project is to identify customers who are likely to churn and understand the key factors driving customer attrition using data analysis and machine learning.

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy)
* **Scikit-learn**
* **Matplotlib / Seaborn**
* **Jupyter Notebook**

---

## 📂 Project Structure

```
customer-churn-analysis/
│
├── notebooks/
│   └── churn_analysis.ipynb
├── outputs/
│   └── charts & visualizations
├── README.md
└── requirements.txt
```

---

## 🔍 Exploratory Data Analysis (EDA)

Key findings from data analysis:

* 📈 Higher **Days Since Last Purchase** → Higher churn
* 📉 Lower **Total Purchases** → Higher churn
* 📉 Lower **Login Frequency** → Higher churn
* 📞 Higher **Customer Service Calls** → Higher churn
* 💰 **Lifetime Value** showed weaker direct impact

---

## 🧩 Customer Segmentation (RFM)

Customers were segmented based on:

* **Recency**
* **Frequency**
* **Monetary Value**

### Segments Identified:

* 🔴 At Risk (~58%)
* 🟡 Recent Customers (~22%)
* 🟢 Loyal Customers (~17%)
* ⭐ Best Customers (~3%)

---

## 🤖 Model Development

### 🔹 Logistic Regression (Baseline)

* Accuracy: **77%**
* Recall (Churn): **42% → 74% (after class balancing)**

### 🌲 Random Forest (Final Model)

* Accuracy: **91.6%**
* Recall (Churn): **76%**
* Precision: **93%**
* F1 Score: **84%**

✅ Selected as final model due to superior performance and better churn detection.

---

## 🔝 Key Features Driving Churn

Top factors identified:

* Customer Service Calls
* Lifetime Value
* Cart Abandonment Rate
* Age
* Discount Usage Rate
* Days Since Last Purchase
* Engagement metrics (Login, Email, Session)

---

## 💡 Business Insights

* Customer inactivity is the strongest indicator of churn
* Low engagement leads to higher churn probability
* High-value customers are also at risk
* Behavioral patterns are more important than monetary metrics

---

## 🎯 Business Recommendations

* 📩 Launch re-engagement campaigns for inactive users
* 🎯 Personalize offers for low-frequency customers
* 🛠 Improve customer support experience
* 🎁 Implement loyalty programs
* 🔔 Monitor key churn indicators

---

## 🚀 Final Outcome

* Built a high-performance churn prediction system
* Achieved **91.6% accuracy with strong recall (76%)**
* Enabled early identification of at-risk customers
* Provided actionable insights for business decision-making

---

## 🧠 Conclusion

This project demonstrates how combining **data analysis, customer segmentation, and machine learning** can help businesses proactively reduce churn and improve customer retention strategies.

---

## 📌 Future Improvements

* Hyperparameter tuning
* Use of advanced models (XGBoost)
* Deployment as a web application
* Real-time churn prediction system

---

## 📎 Author

**Bhushan**
Aspiring Data Analyst | Python | SQL | Machine Learning

---

