# 📘 Likelihood to Purchase Loan – Classification  
Predict whether a customer is likely to purchase a loan using classification models to support targeted marketing strategies.

---

## 🔍 Overview  
- **Goal:** Build a predictive model to classify customers based on their likelihood of purchasing a loan.  
- **Problem Type:** Binary Classification  
- **Dataset:** Bank marketing dataset containing customer demographic and socioeconomic attributes.

---

## 🧭 Context  
Banks frequently run marketing campaigns to promote loan products, but broad outreach can be costly and inefficient.  
Predicting which customers are more likely to purchase a loan enables more focused marketing efforts, improves campaign efficiency, and increases conversion rates.

This project applies supervised machine learning techniques to identify customers with higher purchase likelihood and translate model results into actionable marketing strategies.

---

## 📊 Data Summary  
- **Target Variable:** Likelihood of purchasing a loan (yes/no)  
- **Key Features:**  
  - Demographic information (education level, income, family size)  
  - Customer profile attributes  
- **Data Notes:**  
  - Mix of categorical and numerical variables  
  - Customer information quality directly impacts model performance  

---

## 🛠 Methods & Concepts Used  
- **Preprocessing:**  
  - Encoding categorical variables  
  - Feature selection  
  - Train/test split  

- **Modeling:**  
  - Decision Tree classifiers  
  - Pre-Pruning vs. Post-Pruning model comparison  
  - Model selection based on classification metrics  

- **Techniques:**  
  - Performance evaluation using precision, recall, and accuracy  
  - Model interpretability through feature importance  

---

## 💡 Actionable Insights  

- Use the **Post-Pruning Decision Tree model** for marketing purposes, as it outperforms the Pre-Pruning model across most evaluation metrics, particularly **Recall**. This is critical because the primary objective is to identify as many potential loan purchasers as possible, even at the cost of higher false positives.

- When targeting prospects outside the existing customer database, prioritize **high-income, highly educated individuals with three or more family members**, as these demographic groups show higher likelihood of purchasing a loan.

- Ensure that **customer information is accurate and up to date**, especially for **Education, Income, and Family size**, as these variables are the most important predictors in the selected model.

---

## 👤 Author  
**Henrique Barbosa**  
GitHub: https://github.com/henriqueb-data/
