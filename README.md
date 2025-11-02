# 🧠 Customer Churn Prediction using Machine Learning

This project predicts whether a customer will churn or not based on various customer features using different machine learning models.  
It was developed entirely in **Google Colab** and includes both `.ipynb` and `.py` files for flexibility.

---

## 📂 Files Included
- `customer_churn_project.ipynb` → Colab notebook  
- `customer_churn_project_py.py` → Exported Python script  
- `README.md`  
- `.gitignore`  
- `requirements.txt`

---

## 📊 Project Workflow
1. Load dataset (`customer_churn (3).csv`) from **Kaggle**  
2. Data cleaning and exploration (EDA)  
3. Visualize key patterns:
   - Distribution of tenure and monthly charges  
   - Churn counts and internet service types  
4. Regression:
   - Simple Linear Regression (MonthlyCharges ~ tenure)  
5. Classification:
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest Classifier  
6. Evaluate models using confusion matrix, accuracy, and classification report.

---

## 🧮 Machine Learning Models Used
- Simple Linear Regression  
- Logistic Regression (Binary & Multivariate)  
- Decision Tree Classifier  
- Random Forest Classifier  

---

## ⚙️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Google Colab  

---

## 🧾 Dataset
The dataset used is **Customer Churn Dataset**, taken from **Kaggle**.  
Ensure the dataset file `customer_churn (3).csv` is placed in the same directory as your notebook/script.

You can download similar dataset from Kaggle (https://www.kaggle.com/)

---

## 📈 Results Summary
- Visual insights on tenure, internet services, and churn ratio.  
- Comparison of Decision Tree, Random Forest, and Logistic Regression accuracy.  
- Random Forest generally performs best for churn classification.

---

## ▶ How to Run
1. Upload both `.ipynb` and `.py` files to your Colab or local setup.  
2. Make sure `customer_churn (3).csv` is in your working directory.  
3. Install dependencies using:
   ```bash
   pip install -r requirements.txt
