# 📊 Customer Churn Prediction – Logistic Regression Model

This project focuses on predicting customer churn in a telecom company using logistic regression. It goes beyond simple prediction by identifying high-risk customer segments, analyzing churn drivers, and offering actionable business recommendations.

---

## 🎯 Objective

To analyze customer behavior, identify key churn indicators, and predict which customers are likely to leave — enabling the business to implement targeted retention strategies.

---

## 🧾 Dataset

- **Source:** [Telco Customer Churn – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Records:** 7,043
- **Target:** `Churn (Yes/No)`
- **Features:** Tenure, Contract Type, Monthly Charges, Payment Method, Internet Services, etc.

---

## 🔍 Key Highlights

- Built a logistic regression model with ~82% accuracy and AUC of 0.85
- Segmented customers into **Low**, **Medium**, and **High** churn risk tiers
- Identified **contract type, tenure, and payment method** as top churn predictors
- Generated business-friendly insights and suggested **retention strategies**
- Visualized findings using **green-themed charts** for professional dashboard-style reporting

---

## 📊 Visual Insights

📌 **Churn Risk Segmentation** – High-risk customers are mostly low-tenure users on month-to-month contracts.
<img src="outputs/churn_risk_segmentation.png" width="400"/>  


📌 **Top Churn Drivers** – Contract type and tenure are the most influential features.   
<img src="outputs/feature_importance.png" width="400"/>  


---

## 📈 Model Performance

- **Accuracy:** 82%
- **ROC AUC:** 0.85
- **Precision/Recall:** Balanced
- Evaluated using confusion matrix and ROC curve

---

## 💡 Business Recommendations

- Convert high-risk, month-to-month users to long-term plans
- Offer loyalty programs for customers with <12 months tenure
- Streamline payment experience for electronic check users

---

## 📄 PDF Summary Report

Want a quick one-page overview of the entire analysis, visuals, insights, and business recommendations?

👉 [**View Churn Analysis Report (PDF)**](https://github.com/jan257/churn-analytics-business-case/blob/main/Customer%20Churn%20Analysis%20%26%20Prediction.pdf)

---

## 🛠 Tech Stack

- Python, Pandas, Scikit-learn, Matplotlib, Seaborn
- Logistic Regression
- Model Explainability
- Visual Reporting

---

## 📁 Project Structure

```
customer-churn/
├── data/
│   └── telco_churn.csv
│   └── churn_predictions.csv
├── churn_model.ipynb
├── logistic_churn_model.pkl
└── Customer Churn Analysis & Prediction.pdf

```
---

## 👩‍💻 Author

**Jahnavi P**  
📍 Bangalore, India  
🔗 [LinkedIn](https://www.linkedin.com/in/jahnavi-p-a68788233) 

---

