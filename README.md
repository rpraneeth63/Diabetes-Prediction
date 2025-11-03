# 🩺 Diabetes Prediction using Machine Learning

## 📘 Project Overview
This project aims to predict whether a person is likely to have diabetes based on various medical attributes such as glucose level, blood pressure, BMI, age, and more.  
By leveraging machine learning classification algorithms, this model helps in early detection and prevention of diabetes.

## 📂 Dataset
The dataset used is the **Pima Indians Diabetes Database**, publicly available from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).  
It contains **768 records** and **8 independent variables**, along with one target column indicating diabetes presence (1) or absence (0).

| Feature | Description |
|----------|-------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body mass index (weight in kg/(height in m)^2) |
| DiabetesPedigreeFunction | Diabetes pedigree function (genetic risk) |
| Age | Age in years |
| Outcome | 1 = Diabetic, 0 = Non-Diabetic |

## 🧠 Algorithms and Models Used
Several classification algorithms were tested to find the best-performing model:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

The final model was selected based on accuracy, precision, recall, and F1-score performance metric

## ⚙️ Technologies Used
- **Python 3.x**
- **NumPy** — numerical operations  
- **Pandas** — data manipulation and cleaning  
- **Matplotlib / Seaborn** — data visualization  
- **Scikit-learn (sklearn)** — machine learning model training and evaluation  
- **Jupyter Notebook / VS Code** — development environment  

## 🧩 Project Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Outlier detection
   - Feature scaling (StandardScaler)
2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix
   - Feature importance visualization
3. **Model Building**
   - Splitting dataset into train/test sets
   - Training multiple ML models
4. **Model Evaluation**
   - Using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
5. **Model Deployment (Optional)**
   - Streamlit/Flask web app integration for prediction interface

## 💻 Installation and Setup

**1. Navigate into the project folder**
cd Diabetes-Prediction

**2. Install required libraries**
pip install -r requirements.txt


(If you don’t have a requirements.txt, you can install manually:)

pip install numpy pandas matplotlib seaborn scikit-learn

**3. Run the Jupyter Notebook or Python script**
jupyter notebook Diabetes_Prediction.ipynb
or
python diabetes_prediction.py

## 📊 Results
Model	Accuracy	F1-Score
Logistic Regression	78%	0.76
Random Forest	82%	0.80
SVM	79%	0.77

The Random Forest Classifier achieved the best results with an overall accuracy of ~82%.

## 🚀 Future Scope

Integrate the model into a web application using Streamlit or Flask

Improve performance using hyperparameter tuning or deep learning models

Expand dataset to include more demographic features

Deploy as an API or mobile app for clinical use
