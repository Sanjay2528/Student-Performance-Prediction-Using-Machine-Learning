# Student Performance Predictor Using Machine Learning

## 1. Project Overview

Student Performance Predictor is a Machine Learning project that predicts a
student's final academic score based on different academic and personal
factors such as study hours, attendance, previous marks, assignment scores,
and internal assessment marks.

The project demonstrates the basic Machine Learning workflow, including data
preprocessing, exploratory data analysis, model training, model evaluation,
and prediction.

## 2. Objectives

- To predict student academic performance using Machine Learning.
- To identify factors that affect student performance.
- To preprocess and analyze student data.
- To train Machine Learning models for prediction.
- To evaluate and compare the performance of different models.
- To predict the expected final score for a student.

## 3. Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Streamlit

## 4. Machine Learning Models

The project uses the following Machine Learning algorithms:

- Linear Regression
- Random Forest Regression

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

## 5. Dataset

The dataset contains information about students and their academic
performance.

### Input Features

- Study Hours
- Attendance
- Previous Marks
- Assignment Score
- Internal Assessment
- Sleep Hours
- Class Participation

### Target Variable

The target variable is the student's final academic score.

## 6. Project Workflow

The project follows these steps:

1. Load the dataset.
2. Check and clean the data.
3. Perform exploratory data analysis.
4. Select relevant features.
5. Split the data into training and testing sets.
6. Train the Machine Learning models.
7. Evaluate the models.
8. Compare model performance.
9. Save the best-performing model.
10. Use the trained model to predict student performance.

## 7. Project Structure

```text
student-performance-predictor/
│
├── dataset/
│   └── student_performance.csv
│
├── models/
│   └── model.pkl
│
├── notebooks/
│   └── analysis.ipynb
│
├── app.py
├── train_model.py
├── model.py
├── requirements.txt
├── README.md
└── .gitignore
