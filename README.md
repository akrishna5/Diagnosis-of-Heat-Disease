# Diagnosis of Heart Disease

---

## We have used a variety of Machine Learning algorithms, implemented in Python, to predict the presence of heart disease in a patient

## This is a classification problem, with input features as a variety of parameters, and the target variable as a binary variable, predicting whether heart disease is present or not

---

> Dataset = heart.csv

## Attribute Information

## It is composed of 14 attributes which are age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise induced angina, oldpeak — ST depression induced by exercise relative to rest, the slope of the peak exercise ST segment, number of major vessels and Thalassemia (blood disorder)

> Dataset columns:

### age: The person’s age in years

### sex: The person’s sex (1 = male, 0 = female)

### cp: chest pain types

    — Value 0: asymptomatic
    — Value 1: atypical angina
    — Value 2: non-anginal pain
    — Value 3: typical angina

### trestbps: The person’s resting blood pressure (mm Hg on admission to the hospital)

### chol: The person’s cholesterol measurement in mg/dl

### fbs: The person’s fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)

### restecg: resting electro-cardiographic results

    — Value 0: showing probable or definite left ventricular hypertrophy by Estes’ criteria
    — Value 1: normal
    — Value 2: having ST-T wave abnormality (T wave inversions or ST elevation or depression of > 0.05 mV)

### thalach: The person’s maximum heart rate achieved

### exang: Exercise induced angina (1 = yes; 0 = no)

### oldpeak: ST depression induced by exercise relative to rest

### slope: the slope of the peak exercise ST segment

    - Value 0: downsloping
    - Value 1: flat
    - Value 2: upsloping

### ca: The number of major vessels (0–3)

### thal: A blood disorder called thalassemia

    - Value 0: NULL (dropped from the dataset previously)
    - Value 1: fixed defect (no blood flow in some part of the heart)
    - Value 2: normal blood flow
    - Value 3: reversible defect (a blood flow is observed but it is not normal)

### target: Heart disease (1 = NO , 0 = YES)

---

## Machine Learning algorithms used

1. Logistic Regression
2. Support Vector Machine (SVM)
3. Decision Tree Classification
4. Random Forest Classification

---

### In Future

Ensemble models like

1. XGBoost Classification
2. AdaBoost
3. Gradient Boosting

---
