
# Student Dropout Prediction using Machine Learning

## Project Goal

**The main goal of this project is to predict student dropout rates**. By analyzing student performance, the model aims to identify at-risk students and provide actionable insights for educators.

# Project Overview
This project presents a Machine Learning-based system to predict student dropout risk, helping institutions take proactive steps to improve academic outcomes. It processes educational data to identify patterns that correlate with student success or dropout likelihood, making it a valuable decision-support tool for teachers and administrators.

The solution integrates:

➤ Smart classification models (Decision Tree, Random Forest) with high accuracy (≈85%)

➤ Clean, efficient data preprocessing and feature engineering

➤ Evaluation using cross-validation, confusion matrix, and classification reports

➤ Optional deployment-ready Flask framework for integration into real-time applications

## Key Highlights

- Developed using **Random Forest** and **Decision Tree Classifiers**
- Achieved **85.4% accuracy** on the test set
- Implemented **cross-validation** for model reliability
- Focused on practical **real-world impact for educators**
- Created using **Python**, **Pandas**, **Scikit-learn**, **Seaborn**, and **Matplotlib**
- Deployed a simple **Flask** application for real-time predictions

## Dataset

- Source: [Kaggle Student Data](https://www.kaggle.com/datasets)
- Contains academic, behavioral, and engagement metrics
- Target variable: **Class** (L = Low risk, M = Medium risk, H = High risk)

## Features Used

- Demographics (Gender, Nationality, Place of Birth)
- Academic Info (Grade, Section, Semester)
- Behavioral Patterns (Raised Hands, Visited Resources, Announcements Viewed, Discussion Participation)
- Parent Survey Responses
- Student Absence Days

## Machine Learning Pipeline

1. **Data Cleaning** and preprocessing
2. **EDA** to visualize and understand feature impact
3. Feature encoding and normalization
4. Training with **Decision Tree** and **Random Forest**
5. Evaluation using **confusion matrix**, **classification report**, and **cross-validation**
6. Model Deployment with **Flask**

## Model Performance

- **Accuracy**: 85.4%
- **Cross-Validation Score (Mean)**: 79.1%
- **F1-Score**: High performance for both medium and high-risk students
- **Confusion Matrix**: Strong prediction of high-risk students

## Real-World Use Case

> “With over 100+ students in a class, it becomes difficult for teachers to track individual performance manually. This model acts as a **smart assistant**, flagging at-risk students based on behavior and engagement — ultimately helping reduce dropout rates.”

## Tools & Technologies

- Python (Jupyter Notebook)
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Flask (for web app)
- GitHub + Kaggle (for collaboration & sharing)

## Files in this Repository

- `Student_Dropout_Prediction.ipynb`: Full ML project notebook
- `README.md`: Project documentation
- (Optional) `app.py`: Flask app for deployment
- (Optional) `templates/index.html`: Web interface

## Author

**[Ram kumar S]**  
B.Tech in Artificial Intelligence & Data Science  
Passionate about applying ML to solve real-world problems  
[www.linkedin.com/in/
ramsaravanakumar
]| [https://www.kaggle.com/code/ramsaravanakumar/student-dropout-prediction-using-ml-ramkumar-s]
