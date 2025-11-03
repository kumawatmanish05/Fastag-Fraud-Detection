# 🚗 FASTag Fraud Detection System 💳⚠️  
A machine learning-powered system to detect fraud in **FASTag toll transactions**.  
This project focuses on **EDA, data preprocessing, feature engineering, and model development** to identify fraudulent activities.

---

## 📌 Project Overview  
The goal of this project is to build a model that can differentiate between **legitimate** and **fraudulent** FASTag transactions.  

### Workflow includes
- ✅ Data Preprocessing
- ✅ Exploratory Data Analysis (EDA)
- ✅ Feature Engineering
- ✅ Label Encoding
- ✅ Model Building & Evaluation

---

## 📂 Dataset  
Dataset used: **Synthetic FASTag Fraud Dataset (Kaggle)**  

### Dataset Contains:
- Transaction amount  
- Vehicle details  
- Toll plaza location  
- Transaction category  
- Fraud/Non-fraud indicator  

> ⚠️ This dataset is fictional and meant for learning and practice only.

---

## 🔍 Methodology  

### 🧹 Data Preprocessing  
- Handle missing values  
- Encode categorical attributes  
- Normalize / scale numerical variables  

### 📊 Exploratory Data Analysis  
- Fraud vs Non-Fraud frequency  
- Amount distribution  
- Category-wise fraud frequency  
- Correlation heatmap  

### ⚙️ Feature Engineering  
- Add meaningful variables  
- Reduce noise  
- Select important fraud indicators  

### 🤖 Model Training  
Models used:  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- SVM  
- K-Nearest Neighbors  

### 🧾 Evaluation Metrics  
- Accuracy  
- Precision  
- Recall  
- F1-Score  

---

## 📈 Visualizations  

| Plot | Preview |
|------|--------|
Fraud vs Non-Fraud Count | ![](images/fraud_count_barplot.png)
Transaction Distribution | ![](images/transaction_distribution.png)
Fraud by Vehicle Type | ![](images/fraud_category_plot.png)
Correlation Heatmap | ![](images/correlation_heatmap.png)
Model Accuracy Comparison | ![](images/model_accuracy_comparison.png)
Confusion Matrix | ![](images/confusion_matrix.png)

> 📎 *Images auto-saved via the notebook code*

---

## ⭐ Key Findings  

| Insight | Summary |
|--------|--------|
🚨 Highly Imbalanced Dataset | Fraud cases very low → handled with resampling/weights  
💡 Top Predictors | Vehicle type & transaction amount  
🏆 Best Model | Decision Tree showed highest accuracy among tested models  

---

## 🛠 Tech Stack  

| Category | Tools |
|--------|------|
Language | Python 🐍  
Libraries | Pandas, NumPy, Scikit-Learn  
Visualization | Matplotlib, Seaborn  
Environment | Jupyter Notebook  

---

## ▶️ How to Run

```bash
git clone <repo_link>
cd fastag-fraud-detection
pip install -r requirements.txt
jupyter notebook

