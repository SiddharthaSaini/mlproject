## End to End Machine Learning Project

# 🎓 Student Exam Performance Indicator

🚀 **Live Demo:** https://mlproject-a8sw.onrender.com  

An end-to-end **Machine Learning web application** that predicts a student’s **mathematics exam score** based on demographic information and academic performance.  
The project demonstrates the complete ML lifecycle — from data preprocessing and model training to deployment on the cloud.

---

## 📌 Project Overview

The **Student Exam Performance Indicator** estimates a student’s expected math score using the following features:

- Gender  
- Race/Ethnicity  
- Parental Level of Education  
- Lunch Type  
- Test Preparation Course  
- Reading Score  
- Writing Score  

The trained model is deployed using **Flask** and hosted on **Render**, enabling real-time predictions through a simple and user-friendly web interface.

---

## 🧠 Machine Learning Workflow

1. **Data Ingestion**
   - Load raw dataset and split into training and testing data

2. **Data Transformation**
   - Handle categorical and numerical features
   - Feature encoding and scaling
   - Save preprocessor as an artifact

3. **Model Training**
   - Trained and evaluated multiple regression models:
     - Linear Regression
     - Decision Tree Regressor
     - Random Forest Regressor
     - Gradient Boosting Regressor
     - AdaBoost Regressor
     - XGBoost Regressor
     - CatBoost Regressor
   - Selected the best-performing model using **R² Score**

4. **Model Persistence**
   - Saved trained model and preprocessor using pickle

5. **Prediction Pipeline**
   - Accepts user input
   - Applies preprocessing
   - Generates predicted exam score

6. **Deployment**
   - Flask-based web application
   - Deployed on **Render Cloud**

---

## 🖥️ Application Features

- 📊 Real-time exam score prediction  
- 🧩 Interactive web form for user input  
- ⚙️ End-to-end ML pipeline integration  
- ☁️ Cloud deployment with public access  

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Machine Learning:** Scikit-learn, CatBoost, XGBoost  
- **Data Processing:** Pandas, NumPy  
- **Web Framework:** Flask  
- **Deployment Platform:** Render  
- **Version Control:** Git & GitHub  

---

