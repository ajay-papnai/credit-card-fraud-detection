# 💳 Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The goal is to build an efficient classification model that can accurately identify fraud cases from highly imbalanced transaction data.

---

## 📌 Project Overview

Credit card fraud is a major issue in financial systems. Since fraudulent transactions are very rare compared to legitimate ones, traditional models often fail to detect them effectively.  
In this project, we apply data preprocessing, exploratory data analysis, and machine learning models to tackle this challenge.

---

## 📂 Dataset Description

- The dataset contains **credit card transactions** made by European cardholders.
- Features are numerical and anonymized for privacy.
- The target column:
  - `Class = 0` → Legitimate transaction  
  - `Class = 1` → Fraudulent transaction
- The dataset is **highly imbalanced**, which makes fraud detection challenging.

---

## 🛠️ Technologies Used

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🔍 Steps Performed

### 1. Data Loading & Understanding
- Loaded the dataset and examined its structure
- Checked for missing values and class distribution

### 2. Exploratory Data Analysis (EDA)
- Visualized class imbalance
- Analyzed feature distributions
- Identified patterns in fraudulent vs non-fraudulent transactions

### 3. Data Preprocessing
- Feature scaling using StandardScaler
- Splitting data into training and testing sets
- Handling class imbalance

### 4. Model Training
Machine learning models used: 
- Random Forest Classifier  

### 5. Model Evaluation
Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📊 Results & Insights

- Accuracy alone is **not sufficient** due to class imbalance.
- **Precision and Recall** are critical for fraud detection.
- Random Forest performed better in identifying fraudulent transactions compared to simpler models.

---

## 📈 Visualization

- Confusion Matrix for model performance
- Class distribution plots
- Feature analysis plots

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/ajay-papnai/credit-card-fraud-detection.git
    ```

2. Navigate to the project directory:
    ```bash
    cd credit-card-fraud-detection
    ```


3. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```


4. Open the notebook:
    ```bash
    jupyter notebook credit-card-fraud-detection.ipynb
    ```