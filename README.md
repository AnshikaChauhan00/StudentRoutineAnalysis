# StudentRoutineAnalysis

## Project Overview

The **Student Daily Routine Predictor** aims to build a machine learning model that provides a recommended daily routine for students based on their current habits Based on data collected through surveys from 100 students, the model takes into account various parameters such as study hours, sleep, exercise, social activities, and academic focus level. With this data, the model provides a personalized routine suggestion for the next day to help students better allocate time for essential tasks.

### Project Outline
1.Data Acquisition (Survey of 100 People):
Collect data from 100 students, including features such as:
Age, year of study, primary area of study, study hours, exercise hours, sleep hours, class hours, other activities, difficulty in maintaining routine, time management challenges, and total hours spent.

2.Algorithm Design for Time Management:
A custom algorithm is designed to analyze common issues in student routines, such as lack of time for sleep, study, or exercise.An algorithm that adjusts suggestions for a balanced routine, improving the student’s productivity and well-being.

3.User Interface (UI):
A user-friendly interface was created to collect data and allow students to input their daily routines conveniently. The UI captures key metrics from each student, which are then processed and fed into the machine learning model for prediction.

4.Association Rule Mining:
Using association rule mining (Apriori algorithm), the model identifies patterns in student behavior and routine data.These insights help uncover common patterns and correlations, which inform the model's routine suggestions and provide actionable insights on student habits.

5.Python-Based Implementation:
The entire system is built in Python, leveraging libraries like `pandas`, `scikit-learn`, and `mlxtend`.The project structure includes Python scripts for data preprocessing, model training, and routine generation.

### Purpose and Benefits
This project is to assist students in managing their time effectively by analyzing their daily activities and generating a balanced routine for the following day. Using machine learning, the model analyzes individual routines and time allocation to identify patterns and common challenges in time management. Based on this analysis, the system provides actionable recommendations that help students prioritize essential activities, reduce stress, and increase productivity.By using data-driven insights and personalized suggestions, the project encourages students to adopt healthier and more productive routines.
