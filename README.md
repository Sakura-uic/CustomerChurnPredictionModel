# 📊 Customer Churn Prediction Model

<p align="center">
  <b>Predicting customer behavior using Machine Learning</b><br>
  <i>Helping businesses reduce churn and improve retention</i>
</p>

---

## 🚀 Overview
Customer churn is one of the biggest challenges faced by subscription-based businesses. Losing customers directly impacts revenue, making it essential to identify churn patterns early.

This project builds a **Machine Learning model** to predict whether a customer is likely to churn or not, using the **Telco Customer Churn dataset**.

It demonstrates a complete **end-to-end ML pipeline**, from raw data to actionable insights.

---

## 🎯 Objectives
- 🔍 Identify customers at high risk of churn  
- 📊 Analyze factors influencing customer decisions  
- 💡 Enable businesses to take proactive retention actions  
- 📉 Reduce customer loss and improve profitability  

---

## 🧠 Machine Learning Pipeline

```
Data Collection → Data Cleaning → EDA → Feature Engineering → Model Training → Evaluation
```

---

## 📂 Dataset Description
- **Dataset:** Telco Customer Churn  
- **Target Variable:** `Churn` (Yes / No)

### Features include:
- 👤 Customer demographics (gender, senior citizen, etc.)
- 📦 Services subscribed (internet, phone, streaming)
- 💳 Account details (tenure, contract type, payment method)
- 💰 Billing information (monthly charges, total charges)

---

## 🧹 Data Preprocessing

To ensure high-quality model performance, the following steps were performed:

- ✔️ Converted `TotalCharges` to numeric  
- ✔️ Handled missing values  
- ✔️ Removed duplicate entries  
- ✔️ Encoded categorical variables (Yes/No → 1/0)  
- ✔️ Applied One-Hot Encoding for multi-category features  
- ✔️ Dropped irrelevant column (`customerID`)  

---

## 📊 Exploratory Data Analysis (EDA)

Key insights derived from the data:

- 📈 Customers with **higher monthly charges** show higher churn rates  
- 🔁 **Month-to-month contracts** are more likely to churn  
- ⏳ Customers with **shorter tenure** tend to leave early  
- 🔗 Strong correlations exist between contract type and churn  

---

## ⚙️ Model Development

### 🤖 Algorithm Used:
**Logistic Regression**

### ✅ Why Logistic Regression?
- Simple yet powerful baseline model  
- Highly interpretable  
- Efficient for binary classification problems  
- Provides probability-based predictions  

---

## 🔧 Model Training

- 📌 Train-Test Split: **80% / 20%**  
- ⚖️ Stratified sampling to maintain class balance  
- 📏 Feature scaling using `StandardScaler`  
- ⚠️ Class imbalance handled using:
  ```python
  class_weight = 'balanced'
  ```

---

## 📈 Model Evaluation

The model was evaluated using multiple performance metrics:

- ✔️ Accuracy  
- ✔️ Confusion Matrix  
- ✔️ Precision, Recall, F1-score  
- ✔️ ROC-AUC Score  

### 📌 Key Observations:
- Balanced performance across classes  
- Improved recall for churn prediction  
- Reliable probability outputs for decision-making  

---

## 🛠️ Tech Stack

| Category        | Tools Used |
|----------------|-----------|
| Language        | Python 🐍 |
| Data Handling   | Pandas, NumPy |
| Visualization   | Matplotlib, Seaborn |
| ML Algorithms   | Scikit-learn |

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Customer Churn.ipynb   # Main notebook with full pipeline
├── README.md              # Project documentation
├── dataset.csv            # Dataset (optional)
```

---

## 💡 Future Improvements

- 🚀 Implement advanced models:
  - Random Forest  
  - XGBoost  
  - Neural Networks  

- 🔧 Hyperparameter tuning for better performance  
- 🌐 Deploy using Flask / Streamlit  
- 📊 Build interactive dashboards  
- ⚡ Real-time churn prediction system  

---

## 📌 Conclusion
This project highlights how machine learning can be effectively used to **predict customer churn and generate valuable business insights**.

By identifying at-risk customers early, companies can:
- Improve retention strategies  
- Enhance customer experience  
- Increase long-term revenue  

---

## 🙌 Author

**Shreya Katiyar**  
🎓 B.Tech CSE Student  
💡 Aspiring Data Scientist & AI Engineer  

---

<p align="center">
⭐ If you found this project useful, consider giving it a star!
</p>
