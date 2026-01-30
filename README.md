# Diabetes Prediction using SVM

This repository contains a Machine Learning project that utilizes **Support Vector Machines (SVM)** to predict whether a patient has diabetes based on specific health metrics.

## 🚀 Project Overview
The goal of this project is to build a predictive model that can assist healthcare providers in identifying high-risk patients. By analyzing data such as Glucose levels, BMI, and Insulin, the SVM classifier identifies patterns to categorize patients as Diabetic or Non-Diabetic.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * `Scikit-learn` (for SVM modeling)
    * `Pandas` & `NumPy` (for data manipulation)
    * `Matplotlib` & `Seaborn` (for data visualization)

## 📊 Dataset
The model is trained on the **PIMA Indians Diabetes Dataset**. It includes several medical predictor variables and one target variable (`Outcome`):
* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

## ⚙️ Workflow
1. **Data Collection:** Importing the healthcare dataset.
2. **Data Pre-processing:** Handling missing values and standardizing data (crucial for SVM performance).
3. **Train-Test Split:** Dividing the data for training and evaluation.
4. **Model Training:** Implementing the SVM Classifier with a Linear Kernel.
5. **Evaluation:** Checking accuracy scores on both training and test data.

## 📈 Results
* **Training Accuracy:** [Insert % e.g., 78%]
* **Test Accuracy:** [Insert % e.g., 77%]

## 📝 How to Use
1. Clone the repo: `git clone https://github.com/belalw400-gif/Diabetes-Prediction-using-SVM-Python.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook or script: `python diabetes_prediction.py`
