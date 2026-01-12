# 💳 Credit Card Fraud Detection  
### A Machine Learning Classification Project

## 📌 Overview
This project focuses on detecting **fraudulent credit card transactions** using **machine learning classification techniques**.  
Due to the highly imbalanced nature of fraud datasets, the project emphasizes **robust preprocessing, imbalance handling, and proper evaluation metrics** rather than raw accuracy.

The dataset used is a real-world, anonymized credit card transaction dataset made publicly available on Kaggle.

📂 **Dataset:**  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data


## 🎯 Project Objectives
- Identify fraudulent transactions with high precision and recall  
- Handle severe class imbalance effectively  
- Compare machine learning models for fraud detection  
- Evaluate models using appropriate metrics for imbalanced data  


## 🧠 Problem Statement
Credit card fraud detection is a critical challenge in financial systems due to:
- Extremely **imbalanced datasets**  
- High cost of false negatives (missed frauds)  
- Need for fast and accurate predictions  

Traditional accuracy-based evaluation fails in such scenarios.  
This project addresses these challenges using **machine learning and careful performance evaluation**.


## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:**  
  - pandas, numpy  
  - scikit-learn  
  - matplotlib, seaborn  
- **ML Techniques:** Supervised classification  
- **Environment:** Jupyter Notebook  


## 📊 Dataset Description
- Transactions made by European cardholders  
- Features are **numerical and anonymized** using PCA (V1–V28)  
- `Time` and `Amount` represent transaction metadata  
- `Class` is the target variable  
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction  

The dataset is **highly imbalanced**, with fraudulent transactions accounting for a very small percentage of total records.


## 🔄 Methodology
- Data loading and preprocessing  
- Exploratory data analysis (EDA)  
- Handling class imbalance  
- Feature scaling and transformation  
- Training multiple classification models  
- Model evaluation using imbalance-aware metrics  


## 🤖 Modeling Approach
Machine learning models explored include:
- Logistic Regression  
- Decision Tree  
- Random Forest  

Special attention is given to:
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

These metrics are more meaningful than accuracy in fraud detection tasks.

## 📈 Key Insights
- Accuracy alone is misleading for fraud detection  
- Recall is critical to minimize missed fraudulent transactions  
- Ensemble methods perform better in capturing minority class patterns  
- Proper preprocessing significantly improves model performance  


## 🚀 Use Cases
- Financial fraud detection systems  
- Risk analytics in banking and fintech  
- Machine learning portfolio project  
- Academic coursework in applied ML


## 📌 Conclusion
This project demonstrates the application of **machine learning to a real-world, imbalanced classification problem**.  
By focusing on correct evaluation strategies and model comparison, it highlights best practices for **fraud detection in financial datasets**.
 
