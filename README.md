# Diabetes Prediction System

This project uses **Machine Learning** to predict whether a person is diabetic or not based on various health indicators. The model is trained on the **PIMA Indian Diabetes Dataset** and utilizes a **Support Vector Machine (SVM)** classifier.

---

## Problem Statement

The goal is to create a model that can accurately identify individuals who are at risk of diabetes based on medical input data. Early prediction of diabetes can support timely treatment and improved health outcomes.

---

## Dataset Overview

- **Dataset**: PIMA Indian Diabetes Dataset  
- **Source**: [Kaggle - PIMA Indian Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
- **Samples**: 768  
- **Features**:
  - Pregnancies  
  - Glucose  
  - Blood Pressure  
  - Skin Thickness  
  - Insulin  
  - BMI  
  - Diabetes Pedigree Function  
  - Age  
- **Target**:  
  - `0` → Non-Diabetic  
  - `1` → Diabetic

---

## Technologies & Libraries

- Python  
- Pandas  
- NumPy  
- Scikit-learn

---

## Workflow

1. Import Dependencies  
2. Load Dataset  
3. Data Exploration & Understanding  
4. Data Preprocessing  
   - Standardization  
   - Train-test split  
5. Model Training  
   - Support Vector Machine (SVM)  
6. Model Evaluation  
   - Accuracy on training and test data  
7. Prediction System  
   - Manual input using NumPy array

---

## Results

- **Training Accuracy**: ~79%  
- **Test Accuracy**: ~77%  

> *Note: Accuracy may vary based on random state and data splitting.*

---

## How to Run

1. Clone or download this repository.
2. Ensure the dataset (`diabetes.csv`) is accessible in your environment.
3. Run the notebook using Jupyter or Google Colab.

**Dataset link**:  
[Download diabetes.csv](https://drive.google.com/file/d/1xm4sYWf8ItSWnztVF4FcDCh-YtuKNzLn/view?usp=drive_link)

> Modify the file path in the notebook to match your environment if needed.

---

## Future Enhancements

- Try alternative classification algorithms (e.g., Random Forest, Logistic Regression, XGBoost)  

---

## Acknowledgments

- [Kaggle: PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
- Scikit-learn documentation and the open-source Python community
