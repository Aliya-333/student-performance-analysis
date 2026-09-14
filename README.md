Student Performance Analysis Using Python
📊 Project Overview

This project analyzes student performance data using Python to understand the factors that may be associated with academic performance.

The dataset contains information about students' study habits, attendance, assignment scores, midterm scores, final scores, previous GPA, sleep hours, stress level, extracurricular activities, and other factors.

The project demonstrates a basic data analysis workflow using Python.

🎯 Objectives

The main objectives of this project are:

Analyze overall student academic performance
Identify and handle missing values
Detect and remove duplicate records
Compare student performance across departments
Analyze the relationship between study hours and final scores
Analyze the relationship between attendance and final scores
Explore the relationship between sleep, stress, and academic performance
Identify correlations between different numerical variables
Create visualizations to communicate findings
🛠️ Technologies Used
Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook
📁 Project Files
student-performance-analysis/
│
├── student_analysis.ipynb
├── student_performance.csv
└── README.md

Dataset

The dataset contains 50 student records and includes the following information:

Column	Description
Student_ID	Unique student identifier
Age	Student age
Gender	Student gender
Department	Student's academic department
Study_Hours	Average study hours
Attendance_Percentage	Student attendance
Assignment_Score	Assignment marks
Midterm_Score	Midterm examination score
Final_Score	Final examination score
Previous_GPA	Previous GPA
Internet_Access	Whether the student has internet access
Extracurricular	Participation in extracurricular activities
Part_Time_Job	Whether the student has a part-time job
Sleep_Hours	Average hours of sleep
Stress_Level	Student stress level
Parent_Education	Parent's education level
Family_Income	Family income category
🔍 Data Analysis Process
1. Data Loading

The dataset was loaded using Pandas.

import pandas as pd

df = pd.read_csv("student_performance.csv")

2. Data Inspection

The dataset was examined using:

head()
shape
info()
describe()
isnull().sum()
3. Data Cleaning

The dataset was checked for:

Missing values
Duplicate records
Incorrect data types

Missing numerical values were handled using appropriate imputation methods, and duplicate records were removed.

4. Exploratory Data Analysis

The project explores:

Average student scores
Department-wise performance
Gender-wise performance
Study hours vs final score
Attendance vs final score
Stress level vs final score
Sleep hours vs final score
Part-time employment vs academic performance
5. Data Visualization

The following visualizations were created:

Bar charts
Scatter plots
Box plots
Histograms
Correlation heatmap
📈 Key Questions

Some of the questions explored in this project include:

Which department has the highest average final score?
Is study time related to final exam performance?
Is attendance related to final exam performance?
Does stress level appear to affect academic performance?
Is sleep duration associated with final scores?
Do students with part-time jobs have different academic performance?
Which numerical variables have the strongest correlation with final scores?
💡 Key Findings

The analysis was used to identify patterns and relationships within the student dataset.

The results suggest that factors such as study hours, attendance, previous GPA, assignment performance, and midterm performance can show noticeable relationships with final exam scores.

However, correlation does not necessarily mean that one factor causes another.

📌 Conclusion

This project provided practical experience with the basic data-analysis workflow, including data loading, cleaning, exploratory analysis, visualization, and interpretation of results.

It also helped demonstrate how Python can be used to extract useful insights from structured data.

🚀 Future Improvements

Future versions of this project could include:

A larger real-world dataset
Interactive dashboards using Power BI or Tableau
More advanced statistical analysis
Machine learning models to predict student performance
More detailed feature engineering
👨‍💻 Tools

Python | Pandas | Matplotlib | Seaborn | Jupyter Notebook
