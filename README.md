# Student-Grades-Prediction-Analysis
This project predicts student grades using demographic, social, and academic factors from UCI’s Student Performance dataset. It involves data preprocessing, exploratory analysis, and machine learning models to identify key influences on performance and accurately predict final grades (G3).

# 🎓 Student Grades Prediction

This project focuses on predicting student final grades (G3) using demographic, social, and academic-related attributes.
The datasets include information about Math and Portuguese courses from secondary school students.

# 📂 Project Structure
├── Predicting_student_grades.ipynb   # Jupyter Notebook with full analysis & model
├── student-mat.csv                   # Math course dataset
├── student-por.csv                   # Portuguese course dataset
├── README.md                         # Project documentation

# 📊 Dataset Information

The datasets were sourced from the UCI Machine Learning Repository (Student Performance Data Set).
They include demographic, lifestyle, and academic features, such as study time, absences, parental education, and alcohol consumption.

student-mat.csv → Math course dataset

student-por.csv → Portuguese course dataset

Target Variable

G3 → Final grade (0–20)

Example Features

Demographics: age, sex, address (urban/rural), family size

Parental info: education, occupation, cohabitation status

Academics: study time, past failures, absences, paid classes

Social & lifestyle: internet access, free time, alcohol consumption, going out

# 📖 Full data dictionary is included in this README

## 🚀 Project Workflow

Data Preprocessing

Handle missing values

Encode categorical variables

Normalize/scale features

Exploratory Data Analysis (EDA)

Distribution of grades

Correlation heatmap

Impact of social & demographic factors

Model Building

Train-Test Split

Regression models (Linear Regression, Random Forest, etc.)

Hyperparameter tuning

Evaluation

Metrics: R² Score, MAE, RMSE

Compare performance across models

# ⚙️ Installation & Usage

Clone this repository:

git clone [Clone Project Here](https://github.com/AkashTarsariya/Student-Grades-Prediction-Analysis.git)

cd student-grades-prediction


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook Predicting_student_grades.ipynb

# 📈 Results & Insights

Strong correlation between previous grades (G1, G2) and final grade (G3).

Social and lifestyle factors (alcohol consumption, going out) impact performance.

Ensemble models like Random Forest outperform simple linear regression.

# 📌 Future Improvements

Deploy as a web app for interactive grade prediction.

Extend to other datasets or real-time school performance monitoring.

Explore deep learning models for improved accuracy.

## 📸 Sample Dashboard Preview

- ![Power BI Dashboard](https://github.com/AkashTarsariya/Survival-Analytics-Titanic-Dataset-Power-BI-Dashboard/blob/main/Titanic%20Survival%20Insights%20Dashboard%20PNG.png)
