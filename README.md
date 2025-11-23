# Credit Card Fraud Detection

A machine learning project that detects fraudulent transactions using the popular Credit Card Fraud dataset.

This project includes:

- Data exploration & visualization  
- Data preprocessing (scaling, handling imbalance using SMOTE)  
- Model training using Logistic Regression  
- Model evaluation (AUPRC, confusion matrix, ROC curve)

## Dataset

The dataset used is the Credit Card Fraud Dataset commonly available online (e.g., Kaggle).  
It contains transactions made by European cardholders in September 2013.

Features:

- Amount: Transaction amount  
- Time: Seconds elapsed between each transaction  
- V1–V28: PCA-transformed features  

## Class:

- 0 → Non-fraud  
- 1 → Fraud  

## Project Steps

### 1. Exploratory Data Analysis (EDA)

- Class distribution  
- Histograms  
- Box plots  
- KDE plots  
- Scatter plots  
- Data imbalance visualization  

### 2. Preprocessing

- Removing duplicates  
- Standard scaling  
- Handling class imbalance using SMOTE  

### 3. Model

Using Logistic Regression with:

- StandardScaler  
- SMOTE-balanced training  
- Evaluation on test set  

### 4. Evaluation Metrics

- Classification Report  
- Confusion Matrix  
- ROC Curve  
- AUPRC (most important metric due to imbalance)  

## How to Run

Install requirements:

pip install -r requirements.txt


### **2. Open the notebook**


jupyter notebook Credit_Fraud_Detection.ipynb


### **3. Run all cells**
That’s it!

---

## Project Structure



Credit Fraud Detection/
│── Credit_Fraud_Detection.ipynb
│── README.md
│── requirements.txt
│── images/ (optional for visualizations)


---

##  Requirements

Add the following inside `requirements.txt`:



pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn


---

##  Author
**Sai Teja Sree Ponnaganti**

