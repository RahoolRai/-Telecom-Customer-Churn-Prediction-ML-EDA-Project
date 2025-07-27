# 📞 Telecom Customer Churn Prediction – ML & EDA Project

## 📘 Project Overview  
This project involves **Exploratory Data Analysis (EDA)** and **Machine Learning** on a telecom dataset to predict **customer churn**. The dataset includes customer demographics, service usage patterns, contract details, and account information. The project aims to help telecom providers reduce churn through data-driven strategies.

---

## 🎯 Objective  
To identify key factors driving customer churn and develop a **predictive model** that enables **marketing, retention teams, and decision-makers** to proactively manage and reduce churn rates.

---

## 📊 Dataset Description  
- **Source**: Public Telco Customer Churn Dataset  
- **Records**: 7,043 Customers  
- **Features**:
  - 👤 Customer ID  
  - 📅 Tenure  
  - 💸 Monthly & Total Charges  
  - 💼 Contract Type  
  - 📱 Phone & Internet Services  
  - 🔐 Online Security / Backup  
  - 📡 Tech Support / Streaming  
  - 🔄 Payment Method  
  - 🔁 Churn Label (Yes/No)  

---

## 🛠️ Tools Used  
- 🐍 Python  
- 📒 Jupyter Notebook  
- 📚 Pandas  
- 🌊 Seaborn  
- 📉 Matplotlib  
- 🤖 Scikit-learn  
- 🔍 SHAP / LIME *(Model Interpretability)*

---

## 🔑 Key Insights  
- 💳 Customers on **month-to-month contracts** are more likely to churn.  
- 🔐 Lack of **online security & tech support** correlates with higher churn.  
- 💸 Customers with **high monthly charges** tend to churn more often.  
- 🕒 Longer-tenure customers are **less likely to churn**.  
- 🧾 **Electronic check payment method** is common among churned customers.

---

## 🤖 ML Model Summary  
- **Models Tested**: Logistic Regression, Random Forest, XGBoost  
- **Best Accuracy**: ~82% (Random Forest)  
- **Interpretability**: SHAP values used to explain feature importance

---

## 💡 Recommendation  
To reduce churn, telecom companies should:  
- Offer **incentives** for long-term contracts  
- Improve **online support services**  
- Provide **targeted discounts** to high-risk customers  
- Promote **secure payment options** to reduce churn risk

---

## 📁 Project Files  
- `telecom-churn-prediction.ipynb`: Main Jupyter Notebook with full analysis and modeling  
- `plots/`: Folder containing EDA charts and model visuals  
- `model.pkl`: Trained model file (for deployment)

---

## 🏷️ Hashtags  
#DigipexSolutions | Internship Portfolio | #EDA #ChurnPrediction #MachineLearning #CustomerRetention #Python #SHAP #TelecomAnalytics

