# 25JR5A0518-Week-3-day-1-assignment-
README.mb
Project Overview

This project demonstrates the complete Machine Learning workflow using Python and Scikit-learn. The objective is to predict student marks based on study hours, attendance percentage, and assignment completion using a Linear Regression model.

The project covers data exploration, feature selection, train-test splitting, model training, prediction, evaluation, and data visualization.

Dataset

The dataset contains information about student performance.

Features Study_Hours Attendance Assignments Label (Target Variable) Marks

Dataset File:

student_performance.csv

Technologies Used Python Pandas Scikit-learn Plotly NumPy Jupyter Notebook Machine Learning Workflow

1.Data Collection
The student performance dataset was collected and stored in CSV format.

2.Data Exploration
The dataset was analyzed using:

head() tail() shape columns dtypes describe() 3. Feature Selection

Selected Features:

Study_Hours Attendance Assignments

Target Variable:

Marks 4. Train-Test Split

The dataset was divided into:

Training Data: 80% Testing Data: 20% 5. Model Training

A Linear Regression model was trained using the training dataset.

6.Prediction
The trained model was used to predict marks for new student records.

7.Model Evaluation
Performance was evaluated using:

Mean Absolute Error (MAE) R² Score 8. Data Visualization

Interactive visualizations were created using Plotly.

Project Structure

week3-day1-ml-fundamentals

├── student_performance.csv

├── assignment.ipynb

├── ml_workflow.txt

├── answers.txt

├── screenshots/

│ ├── plot1.png

│ ├── plot2.png

│ ├── plot3.png

│ ├── plot4.png

│ └── plot5.png

└── README.md

Visualizations Plot 1

Study Hours vs Marks

Plot 2

Attendance vs Marks

Plot 3

Assignments vs Marks

Plot 4

Regression Line Visualization

Plot 5

Predicted Marks Trend

Model Evaluation Metrics Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

R² Score

Measures how well the model explains the variance in the target variable.

A higher R² Score indicates better model performance.

Sample Prediction

The model predicts marks for students based on:

Study Hours Attendance Assignments 5 80 5 8 90 8 12 95 10 Learning Outcomes

Through this project, the following concepts were learned:

Machine Learning Basics Features and Labels Data Preprocessing Train-Test Split Linear Regression Model Evaluation Prediction Techniques Data Visualization Real-world ML Workflow
