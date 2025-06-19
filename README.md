
# 🏦 PaisaBazaar Banking Fraud Analysis & Credit Score Prediction

This project is a full **EDA + Machine Learning** pipeline developed to analyze customer financial data from PaisaBazaar and predict their **credit scores**. It includes **data preprocessing**, **exploratory data analysis (EDA)**, **visualizations**, **feature engineering**, and **classification modeling** to identify financial behavior and potential fraud indicators.

---

## 📁 Dataset Overview

The dataset contains **customer-level financial and demographic information**, such as:
- Annual income
- Age
- Number of bank accounts
- Credit card activity
- Delayed payments
- Outstanding debt
- Credit history age
- Credit mix
- Payment of minimum amount
- Monthly balance

The **target column** is:
- `Credit_Score` → Categorical (Poor, Standard, Good)

---

## ✅ Objectives

- Perform detailed **exploratory data analysis (EDA)** to identify trends and anomalies.
- Handle **missing data**, incorrect formats, and feature encoding.
- Visualize important patterns with **matplotlib** and **seaborn**.
- Build and evaluate classification models to predict **credit scores**.
- Extract actionable business insights for credit risk management.

---

## 🧼 Data Cleaning

- Converted `Credit_History_Age` (text format) to total months.
- Handled missing values using **mean** (numerical) and **mode** (categorical).
- Imputed categorical features like `Credit_Mix` and `Payment_of_Min_Amount`.
- Used **Label Encoding** for categorical variables.

---

## 📊 Exploratory Data Analysis

- **Distribution analysis** of features like age, credit cards, delayed payments, etc.
- **Correlation heatmaps** and pair plots to understand feature relationships.
- **Box plots & histograms** to spot outliers and skewed distributions.
- Insights drawn:
  - Higher `Outstanding_Debt` correlates with Poor credit score.
  - Customers not paying the minimum amount regularly tend to have worse credit.

---

## ⚙️ Feature Engineering

- Dropped identifiers (`ID`) and low-impact features.
- Created derived features like total credit ratio.
- Scaled continuous variables using `StandardScaler`.

---

## 🤖 Machine Learning Models

Two classification models were trained and evaluated:
1. **Logistic Regression** – Fast, baseline model
2. **Random Forest Classifier** – Best performing, robust to overfitting

📈 **Evaluation Metrics**:
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

## 📌 Results

- Random Forest achieved higher performance.
- Key predictive features:
  - `Outstanding_Debt`
  - `Monthly_Balance`
  - `Num_Bank_Accounts`
  - `Credit_Mix`

---

## 🔍 Insights & Business Use

- Helps identify **high-risk customers** early.
- Supports **automated loan approval** pipelines.
- Useful in **fraud detection**, **risk profiling**, and **credit policy design**.

---

## 🔮 Future Improvements

- Use advanced models like **XGBoost** or **CatBoost**.
- Balance class distribution using **SMOTE**.
- Create an interactive **Streamlit dashboard** for stakeholders.

---

## 📚 Tech Stack

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**

---

## 🧑‍💻 Author

**Chetan Badgujar**  
3nd Year B.Tech Student | Data Science & Machine Learning Enthusiast | Tech Intern]

---

## 📂 File Structure

```

📦PaisaBazaar\_Banking\_Fraud\_Analysis
┣ 📄 PaisaBazaar\_EDA\_ML\_Final\_Updated\_Notebook.ipynb
┣ 📄 README.md

```

---

## 📝 License

This project is for educational purposes only.
```

