# Brain-Stroke-Prediction🧠
## Problem Statement 
According to the World Health Organization (WHO),Brain stroke is the world's second biggest cause of death causing nearly 11% of all deaths. Despite significant advances in healthcare, Brain stroke remains to be a serious public health issue. This highlights the critical need for improved prevention, early identification, and effective precautions should be taken  to minimize the world impact of Brain stroke
## 📌 Project Overview
The Brain Stroke Prediction project leverages machine learning 🤖 to predict the likelihood of a person experiencing a stroke based on various health 🏥 and lifestyle factors. This can assist in early diagnosis and preventive healthcare strategies.
## 📊 Dataset
The dataset consists of 12 features that help in stroke prediction:
# 🧠 Brain Stroke Prediction 🚑

## 📊 Dataset Description  
The dataset consists of **12 features** that help in stroke prediction:  

| 🔢 Feature Name        | 📌 Description |
|--------------------|--------------|
| 🆔 **id**                  | Unique identifier for each patient  |
| 🚻 **gender**              | Gender of the patient (`Male`, `Female`, `Other`)  |
| 🎂 **age**                 | Age of the patient  |
| ❤️ **hypertension**        | Whether the patient has hypertension (`0: No`, `1: Yes`)  |
| 💔 **heart_disease**       | Whether the patient has heart disease (`0: No`, `1: Yes`)  |
| 💍 **ever_married**        | Whether the patient was ever married (`Yes`, `No`)  |
| 🏢 **work_type**           | Type of work (`Private`, `Self-employed`, `Govt_job`, `Children`, `Never_worked`)  |
| 🏡 **Residence_type**      | Type of residence (`Urban`, `Rural`)  |
| 🍬 **avg_glucose_level**   | Average glucose level of the patient  |
| ⚖️ **bmi**                 | Body Mass Index (BMI) of the patient  |
| 🚬 **smoking_status**      | Smoking habits (`formerly smoked`, `never smoked`, `smokes`, `Unknown`)  |
| ⚠️ **stroke**              | Whether the patient had a stroke (`0: No`, `1: Yes`)  |

## 🎯 Objective
The main goal of this project is to develop an accurate machine learning model to predict stroke risk, helping healthcare professionals take preventive measures.
## ⚙️ Methodology
### 1. Data Preprocessing
* ✅ Handling missing values
* ✅ Encoding categorical variables
* ✅ Normalization & feature scaling

### 2. Exploratory Data Analysis (EDA)
* 📊 Feature distribution visualizations
* 🔍 Correlation analysis
* 📈 Identifying key risk factors

### 3. Model Training & Evaluation
* 🤖 Training multiple models:
* Logistic Regression
* Random Forest
* AdaBoost
* 📉 Evaluation using Accuracy, Precision, Recall, F1-score, and ROC-AUC
## 🏆 Model Comparison

| Model                | Training Accuracy | Testing Accuracy | Observations           |
|----------------------|------------------|------------------|------------------------|
| Logistic Regression | 83.33%            | 83.64%             | Balanced performance     |
| Random Forest       | 100%              | 100%                  | Perfect accuracy detected                |
| AdaBoost           | 84.98%             | 83.85%             | Balanced performance                 |

## 📌 Key Takeaways
✅ Age, hypertension, and heart disease are significant predictors of stroke risk.

✅ Random Forest tends to overfit, while AdaBoost provides better generalization.

✅ Feature scaling and balancing techniques (e.g., SMOTE) improve model performance.

## 🚀 Future Improvements
* Hyperparameter tuning for AdaBoost to further optimize performance.
* Adding more features like lifestyle habits, cholesterol levels, and physical activity.
* Deploying the model using Flask or Streamlit for real-time predictions.
