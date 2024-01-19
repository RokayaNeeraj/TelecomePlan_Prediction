# Telecom Logistic Regression Project Summary

This project focuses on developing a Logistic Regression model for a telecom dataset. The process involves various stages, from data preprocessing to model evaluation, with a focus on addressing data imbalance and applying regularization techniques.

## Steps of Analysis

### **1. Importing Libraries and Installing Pandas Profiling**
- **Task:** Set up necessary Python libraries and tools for data analysis.

### **2. Reading and Understanding the Data**
- **Task:** Load and examine the telecom dataset to understand its structure and contents.

### **3. Plotting Data for Outlier Analysis**
- **Task:** Visualize the data to identify and handle outliers.

### **4. Outlier Handling using Lower and Upper Bounds**
- **Task:** Remove extreme outliers to normalize the dataset.

### **5. Assigning Feature and Target Variables**
- **Task:** Define the features (X) and target variable (y) for the Logistic Regression model.

### **6. Handling Missing Values**
- **Task:** Address any missing values in the dataset.

### **7. Checking Multicollinearity with VIF Score**
- **Note:** Retained existing features despite high VIF scores due to low inter-column correlation.

### **8. One Hot Encoding**
- **Task:** Apply One Hot Encoding to categorical variables.

### **9. Feature Scaling**
- **Task:** Scale features to reduce variance and optimize model performance.

### **10. Building Logistic Regression Model**
- **Task:** Develop and train the Logistic Regression model.

## Model Evaluation Results

### Basic Logistic Regression
- **Accuracy:** `0.8286637931034483`

### With Regularization
- **Accuracy:** `0.8286637931034483`
- **Recall:** `0.2937853107344633`
- **AUC:** `0.6242561706801477`
- **Confusion Matrix:** [[717 34] [125 52]]


### After Handling Imbalance
- **Accuracy:** `0.7413793103448276`
- **Recall:** `0.7005649717514124`

### Cross-Validation Results with Imbalance Handling
- **Average Accuracy:** `0.758326533444352`
- **Average Recall:** `0.7604853022739879`
