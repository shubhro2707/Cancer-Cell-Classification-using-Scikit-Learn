# **Breast Cancer Classification Using Naive Bayes**  

## **Overview**  
In this project, I implemented a **Naive Bayes classifier** to predict whether a tumor is **malignant** or **benign** based on given features. The model was trained and evaluated using a dataset containing various tumor characteristics.  

---  

## **Process**  

### **1. Data Loading**  
- Loaded the dataset from a **CSV file**.  
- Removed unnecessary columns (**id, unnamed columns**) to clean the data.  
- Encoded the target variable (**diagnosis**) as:  
  - **1 → Malignant**  
  - **0 → Benign**  

### **2. Data Preprocessing**  
- Separated the dataset into **features (X)** and **target (y)** variables.  
- Split the data into **training (80%)** and **testing (20%)** sets.  
- Applied **feature scaling** using **StandardScaler** to normalize the dataset.  

### **3. Model Training**  
- Used a **Naive Bayes classifier (GaussianNB)** to train the model.  
- The model learned **patterns** from the training data.  

### **4. Model Evaluation**  
- Made **predictions** on the test data.  
- Computed key performance metrics:  
  - **Accuracy**  
  - **Confusion Matrix**  
  - **Classification Report**  
- Generated a **heatmap visualization** of the confusion matrix for better interpretation.  

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
- **pandas** – For data manipulation  
- **numpy** – For numerical computations  
- **matplotlib & seaborn** – For visualization  
- **sklearn (Scikit-learn)** – For machine learning algorithms & model evaluation  

---  

## **Results**  

### **Accuracy:**  
- Achieved an accuracy of **~96.49%**  

### **Confusion Matrix:**  
|   | Predicted Benign | Predicted Malignant |  
|---|----------------|----------------|  
| **Actual Benign** | 70 | 1 |  
| **Actual Malignant** | 3 | 40 |  

### **Classification Report:**  
- **Precision, Recall, and F1-score** indicate **high model performance**.  
- The **Naive Bayes classifier** effectively distinguished between **benign and malignant tumors**, achieving **high accuracy** with **minimal misclassifications**.  
- This approach provides a **simple yet effective method** for **breast cancer detection**.


![image](https://github.com/user-attachments/assets/1279c705-5d20-4eab-b28c-6b382248ba5f)
