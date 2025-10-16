# 🛢️ U.S. Oil & Gas Production & Disposition Analysis (2015–2025)

### Author: Joel Akoun – Data Scientist  
### Date: October 2025  

---

## 🤖 Modeling Approach

Two modeling pipelines were developed:

### ⏳ Time Series Forecasting
- Models: **AR**, **MA**, **ARMA**, **ARIMA**, and **SARIMA**
- ✅ **Best Model:** `SARIMA(1,1,1)(0,1,1,12)` — captured both long-term trends and seasonality with low error (MAPE < 8%)
- **ARIMA** provided strong overall forecasts, while **SARIMA** slightly improved seasonal accuracy

### 🎯 Classification Models
- Models: **Logistic Regression**, **Decision Tree**, **Random Forest**, **Linear SVM**, and **Extra Trees**
- ✅ **Best Model:** **Extra Trees Classifier** – Accuracy ≈ 95%, ROC-AUC ≈ 0.99  
- Strong balance between precision and recall, excellent generalization, and high interpretability

---

## 📈 Results Summary

- **Forecasting:** ARIMA/SARIMA models captured production trends and seasonality effectively  
- **Classification:** Extra Trees accurately identified high-producing operations with 95%+ accuracy  
- **Validation:** Models generalized well across folds, confirming reliability and robustness  

---

## 🔍 Feature Importance & Insights

Production performance is driven by both operational and commodity-related variables:

| Rank | Feature | Insight |
|------|----------|----------|
| 1️⃣ | Is Positive Volume | Strongest indicator of high output |
| 2️⃣ | Volume Class | Reflects operational performance levels |
| 3️⃣ | Disposition Group | How production is managed (Sales, Inventory, Transfer) |
| 4️⃣ | Commodity Type | Oil vs. Gas patterns in production behavior |
| 5️⃣ | Land Category | Onshore production linked with higher yields |

✅ **Key takeaway:**  
Production outcomes are shaped by *what* is produced, *how* it’s handled, and *where/when* it occurs.

---

## 💡 Business Impact

- Enables **data-driven forecasting** of U.S. oil & gas output  
- Supports **strategic planning**, **budgeting**, and **investment prioritization**  
- Helps identify **high-performing operations** for optimization  
- Improves **transparency and policy planning** for energy management  

---

## 🚀 Recommendations

- Implement advanced ensemble methods (e.g., **XGBoost**, **LightGBM**) for even higher precision  
- Incorporate **external drivers** (market prices, weather, regulations)  
- Automate **model retraining** as new ONRR data is released  
- Deploy as a **dashboard or REST API** for real-time decision support  
- Continuously **monitor model drift** for long-term reliability  

---

## 🏁 Conclusion

This project demonstrates how **machine learning and time series modeling** can predict and explain U.S. oil & gas production trends using ONRR data (2015–2025).  
By combining **SARIMA forecasting** and **Extra Trees classification**, we achieved strong accuracy and identified the key operational and commodity factors driving production behavior.  

💪 The results showcase the power of **data-driven forecasting** in improving efficiency, transparency, and decision-making across the U.S. energy sector.

---

## 🧰 Tech Stack
- **Languages & Tools:** Python, Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib, Seaborn, Joblib  
- **Model Types:** ARIMA/SARIMA (Time Series), Extra Trees (Classification)  
- **Environment:** Jupyter Notebook  

---# Us-Oil-Gas-production-disposition
# Us-Oil-Gas-production-disposition
# Us-Oil-Gas-production-disposition
# Us-Oil-Gas-production-disposition
# Us-Oil-Gas-production-disposition
# Us-Oil-Gas-production-disposition
# Us-Oil-Gas-production-disposition
# Us-Oil-Gas-production-disposition
# US-Oil-Gas-Production
# US-Oil-Gas-Production
