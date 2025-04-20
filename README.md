
# Student Dropout Prediction using Machine Learning

# Project Overview

➤This project aims to develop a machine learning model that predicts the likelihood of a student dropping out, based on behavioral and demographic features.
➤The goal is to assist educators in identifying at-risk students early, enabling timely intervention and improved academic outcomes.

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
[www.linkedin.com/in/ramsaravanakumar]| [ramsaravanakumar/kaggle]
