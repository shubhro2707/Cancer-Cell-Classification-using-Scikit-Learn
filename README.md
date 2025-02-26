# **Breast Cancer Classification Using Naive Bayes**  

## **Overview**  
This project implements a **Naive Bayes classifier** to predict whether a tumor is **malignant** or **benign** based on given features. The model is trained and evaluated using a dataset containing various tumor characteristics.  

---  

## **Process**  

### **1. Data Loading**  
- The dataset is **read from a CSV file**.  
- Unnecessary columns (**id, unnamed columns**) are **dropped**.  
- The target variable (**diagnosis**) is encoded as:  
  - **1 → Malignant**  
  - **0 → Benign**  

### **2. Data Preprocessing**  
- Features (**X**) and target (**y**) variables are **separated**.  
- The dataset is **split** into **training (80%)** and **testing (20%)** sets.  
- **Feature scaling** is applied using **StandardScaler** to normalize the dataset.  

### **3. Model Training**  
- A **Naive Bayes classifier (GaussianNB)** is used.  
- The model learns **patterns** from the training data.  

### **4. Model Evaluation**  
- Predictions are made on the **test data**.  
- Performance metrics are computed:  
  - **Accuracy**  
  - **Confusion Matrix**  
  - **Classification Report**  
- A **heatmap visualization** of the confusion matrix is generated for better interpretation.  

---  

## **Architecture**  
### **Input:**  
- **Breast cancer dataset (CSV file)**  

### **Processing:**  
- **Data cleaning & preprocessing**  
- **Feature scaling**  
- **Training with Naive Bayes classifier**  

### **Output:**  
- **Model predictions & evaluation metrics**  

---  

## **Tools and Frameworks Used**  

### **Programming Language:**  
- **Python**  

### **Libraries:**  
- **pandas** – Data manipulation  
- **numpy** – Numerical computations  
- **matplotlib & seaborn** – Visualization  
- **sklearn (Scikit-learn)** – Machine learning algorithms & model evaluation  

---  

## **Results**  

### **Accuracy:**  
- **~96.49%**  

### **Confusion Matrix:**  
|   | Predicted Benign | Predicted Malignant |  
|---|----------------|----------------|  
| **Actual Benign** | 70 | 1 |  
| **Actual Malignant** | 3 | 40 |  

### **Classification Report:**  
- **Precision, Recall, and F1-score** indicate **high model performance**.  
- The **Naive Bayes classifier** effectively distinguishes between **benign and malignant tumors**, achieving **high accuracy** with **minimal misclassifications**.  
- This approach provides a **simple yet effective method** for **breast cancer detection**.


![image](https://github.com/user-attachments/assets/1279c705-5d20-4eab-b28c-6b382248ba5f)
