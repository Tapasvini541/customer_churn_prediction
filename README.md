# Customer Churn Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict customer churn using machine learning techniques. The model analyzes customer data such as age, income, purchases, and membership type to determine whether a customer is likely to churn.

---

## 📂 Dataset

* Source: Kaggle
* Original dataset: Telco Customer Churn dataset
* The dataset was preprocessed to include only the required features:

  * Age (Synthetically generated)
  * Income
  * Purchases
  * Membership
  * Churn

---

## ⚙️ Project Workflow

1. Data Collection from Kaggle
2. Data Cleaning and Preprocessing
3. Conversion of Categorical Data
4. Feature Selection
5. Model Training

   * Logistic Regression
   * Decision Tree
6. Model Evaluation using Accuracy
7. Rule-Based Churn Prediction
8. Model Comparison and Visualization

---

## 🤖 Models Used

### 1. Logistic Regression

* A linear model used for binary classification
* Achieved the highest accuracy

### 2. Decision Tree

* A non-linear model that captures complex patterns
* Moderate performance compared to Logistic Regression

### 3. Rule-Based Model

* Uses predefined conditions
* Simple but less accurate

---

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 80.27%   |
| Decision Tree       | 70.97%   |
| Rule-Based          | 26.53%   |


---

## ⚖️ Key Observations

* Logistic Regression performed the best overall
* Decision Tree showed moderate performance
* Rule-based logic performed poorly due to lack of learning capability
* SMOTE improved class balance but slightly reduced accuracy

---

## 🧠 Conclusion

Logistic Regression achieved the highest accuracy, indicating that the dataset follows a relatively linear pattern.

---

## 🚀 Future Improvements

* Use advanced models like Random Forest or XGBoost
* Perform hyperparameter tuning
* Add more features for better prediction
* Evaluate using Precision, Recall, and F1-score

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 📁 Deliverables

* Jupyter Notebook (.ipynb)
* Cleaned Dataset (.csv)
* README File

---

