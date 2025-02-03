# Titanic Survival Prediction Project

## **Overview**
This project explores the **Titanic dataset** to analyze survival factors and develop a **machine learning model** that predicts whether a passenger survived the disaster. Through **data preprocessing, feature engineering, and model training**, we build a predictive system using **Logistic Regression**.

The project also serves as a demonstration of **data science workflow**—from data cleaning to model evaluation.

---

## **Project Structure**
📂 **data/** – Raw and processed datasets  
📂 **notebooks/** – Jupyter notebooks for analysis and documentation  
📂 **src/** – Python scripts for data cleaning, feature engineering, and model building  
📂 **results/** – Charts, plots, and saved models  

---

## **Steps Taken**
### **1. Data Preprocessing**
- Handled missing values (`Age`, `Embarked`, `Fare`)
- Created new features (`FamilySize`, `Title`)
- Encoded categorical variables (`Sex`, `Embarked`, `Title`)
- Scaled numerical features (`Age`) to improve model performance

### **2. Model Training & Validation**
- Split data into **training and validation sets (80-20 split)**
- Trained a **Logistic Regression model**
- Achieved **validation accuracy of XX%**

### **3. Predictions on Unseen Test Data**
- Applied the same preprocessing steps to the test dataset
- Generated predictions on passengers' survival

---

## **Future Improvements**
🚀 **Try different machine learning models** (e.g., Random Forest, XGBoost)  
🚀 **Optimize hyperparameters** for better accuracy  
🚀 **Feature importance analysis** to see which factors impact survival most  
🚀 **Deploy the model** as a web app using Flask or Streamlit  

---

## **Challenges & Solutions**
Throughout the project, we encountered several **errors** and **fixed them systematically**:

❌ **NaN Values in Encoding** – After mapping categorical variables, `NaN` values appeared in test data.  
✔ **Solution:** Used `.fillna()` to handle missing values before encoding.

❌ **Mismatch Between Training & Test Data** – Some features were missing from test data after transformations.  
✔ **Solution:** Ensured all transformations (scaling, encoding) were applied equally to both datasets.

---

## **Getting Started**
Clone this repository:
```bash
git clone https://github.com/BuddyDudeGuy/titanic_project.git
