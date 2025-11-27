# 🎯 Mine vs Rock Prediction using Machine Learning 

## 📘 Overview  
This project aims to **classify objects as either “Mine” or “Rock”** based on sonar signal data using **Machine Learning techniques**.  
The dataset contains sonar readings bounced off metal cylinders and rocks on the sea floor.  
The goal is to train a model that can accurately differentiate between mines (dangerous underwater explosives) and rocks (natural obstacles).  

---
     
## 🧠 Problem Statement  
Given a set of sonar signals (numerical features), build a classification model that predicts whether the object detected is a **Mine (M)** or a **Rock (R)**.

---

## 📂 Dataset  
- **Dataset Name:** Sonar Data (Mines vs Rocks)  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+%28Sonar%2C+Mines+vs.+Rocks%29)  
- **Attributes:**  
  - 60 numerical features representing sonar signal strength at different angles.  
  - 1 target label: **M (Mine)** or **R (Rock)**  

---

## ⚙️ Technologies Used  
- **Programming Language:** Python  
- **Libraries:**  
  - `numpy` – for numerical computations  
  - `pandas` – for data manipulation  
  - `matplotlib` / `seaborn` – for data visualization  
  - `scikit-learn` – for building and evaluating ML models  

---

## 🧩 Steps Involved  
1. **Data Collection & Loading** – Importing the sonar dataset.  
2. **Data Exploration** – Understanding data types, shape, and distribution.  
3. **Data Preprocessing** – Handling categorical data and feature scaling.  
4. **Splitting Data** – Dividing into training and testing sets.  
5. **Model Training** – Using a **Logistic Regression / SVM / Random Forest** classifier.  
6. **Model Evaluation** – Checking accuracy, confusion matrix, and classification report.  
7. **Prediction System** – Building a simple input-based prediction (Mine or Rock).  

---

## 📈 Model Accuracy  
| Model | Accuracy |
|--------|-----------|
| Logistic Regression | 83–85% |
| Support Vector Machine (SVM) | 86–88% |
| Random Forest Classifier | 88–90% |

*(Accuracy may vary depending on preprocessing and parameter tuning.)*

---
