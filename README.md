# 🏥 Predictive Maternal Health Risk Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)

> Leveraging machine learning to detect high-risk maternal health cases early — enabling timely interventions and better healthcare outcomes.

---

## 📌 Project Overview

Maternal mortality remains a critical global health challenge. This project applies **healthcare data analysis and predictive modeling** to classify patients into risk levels (Low / Mid / High) using key clinical indicators such as blood pressure, blood sugar, heart rate, and body temperature.

---

## 🎯 Objective

To build a reliable predictive model that identifies high-risk maternal health cases early, supporting healthcare professionals in making data-driven decisions.

---

## 📊 Dataset

- **Source:** [Kaggle — Maternal Health Risk Data](https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data)
- **Features used:**

| Feature | Description |
|---|---|
| Age | Patient age |
| SystolicBP | Upper blood pressure value |
| DiastolicBP | Lower blood pressure value |
| BS | Blood sugar level |
| BodyTemp | Body temperature |
| HeartRate | Pulse rate |
| RiskLevel | Target variable (Low / Mid / High) |

---

## 🛠️ Methodology
```
1. Data Preprocessing
   ├── Handling missing values & duplicates
   ├── Removing invalid entries
   └── Outlier detection & removal

2. Exploratory Data Analysis (EDA)
   ├── Correlation heatmap
   └── Boxplots (Age, BP, Blood Sugar vs Risk)

3. Model Training (80/20 Train-Test Split)
   ├── Logistic Regression
   ├── Decision Tree
   ├── Random Forest
   └── Tuned Random Forest (GridSearchCV)
```

---

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|
| Logistic Regression | 86.2% | 78.3% | 66.7% | 72.0% |
| Decision Tree | 93.6% | 90.2% | 85.2% | 87.6% |
| Random Forest | 95.1% | 90.7% | 90.7% | 90.7% |
| **Tuned Random Forest** ✅ | **95.6%** | **90.9%** | **92.6%** | **91.7%** |

> 🏆 **Best Model: Tuned Random Forest** — highest accuracy with best precision-recall balance

---

## 🔍 Key Findings

- **Blood Sugar (BS)** had the strongest correlation with high-risk outcomes (0.62)
- **Logistic Regression** underperformed due to low recall — missing many high-risk cases
- **Random Forest** consistently outperformed simpler models
- **Tuned Random Forest** (GridSearchCV optimized) achieved the best overall performance

---

## 🧰 Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## 👩‍💻 Author

**Shreya Rathod** — Business Analyst | Data Analytics  
📍 New Jersey, USA  
🔗 [LinkedIn](https://www.linkedin.com/in/shreya-rathod009)
