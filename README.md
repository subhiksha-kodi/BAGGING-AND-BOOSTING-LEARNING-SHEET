# 🚀 Bagging & Boosting Algorithms – Learning Sheet  

This project demonstrates the use of **Gradient Boosting** and **XGBoost** for solving classification problems across different datasets. The notebook covers data preprocessing, model training, and evaluation using accuracy and ROC-AUC scores.  

---

## 📌 Project Overview  
Ensemble methods like **Bagging and Boosting** combine multiple weak learners to improve predictive performance.  
- **Bagging** reduces variance by training models on bootstrapped samples.  
- **Boosting** improves accuracy by focusing on misclassified instances iteratively.  

This notebook focuses on **Boosting algorithms**:  
- Gradient Boosting  
- XGBoost  

---

## 📂 Datasets Used  
1. **Healthcare Stroke Dataset** 🧑‍⚕️  
   - Task: Predict the likelihood of a patient having a stroke.  
2. **Bank Loan Dataset** 🏦  
   - Task: Predict loan approval status.  
3. **Wine Quality Dataset** 🍷  
   - Task: Classify wine as good/bad based on chemical properties.  
4. **Mushroom Dataset** 🍄  
   - Task: Classify mushrooms as edible or poisonous.  

---

## ⚙️ Tech Stack  
- **Python 3**  
- **Pandas, NumPy** – Data Handling  
- **Scikit-learn** – Model Training & Evaluation  
- **XGBoost** – Boosting Model  
- **Matplotlib / Seaborn** – Visualizations  

---

## 🧪 Methodology  
1. **Data Preprocessing**  
   - Handling missing values  
   - Label Encoding for categorical variables  
2. **Model Training**  
   - `GradientBoostingClassifier` (Scikit-learn)  
   - `XGBClassifier` (XGBoost)  
3. **Evaluation**  
   - 5-fold Cross-validation  
   - Metrics: **Accuracy** and **ROC-AUC**  

---

## 📊 Results  
- Gradient Boosting and XGBoost consistently achieved **high accuracy and ROC-AUC** across datasets.  
- Boosting models performed well on imbalanced datasets like **Stroke Prediction**.  

---
