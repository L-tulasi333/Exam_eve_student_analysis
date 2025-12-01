# Exam_eve_student_analysis
**Exam Readiness Prediction – Data Analysis & ML Pipeline:**

This project analyzes students’ exam preparation patterns and predicts their exam readiness level using a complete data science workflow — from data cleaning to model building. The dataset contains self-reported information on sleep patterns, study habits, emotional state, time usage, and overall preparedness.

**Project Overview:**

The objective of this project is to understand how different behavioral, psychological, and study-related factors influence a student’s readiness level before an exam.
The project involves:
Comprehensive Exploratory Data Analysis (EDA) using Pandas, NumPy, and visualization libraries.
Data preprocessing including categorical encoding, scaling, and transformation.
Building a full machine learning pipeline using K-Nearest Neighbors (KNN) to predict exam readiness.

**Dataset Description:**

The dataset contains columns related to:
* Demographics: gender
* Behavioral factors: time on social media, gaming, video streaming
* Study patterns: hours studied, study intensity, material covered
* Mental state: fatigue, anxiety, overwhelm
* Sleep patterns: normal sleep vs last night sleep
* Outcome: Readiness Level (Target Variable)
All original survey questions were cleaned and renamed for analysis.

**Data Cleaning & Preprocessing:**

* Cleaned and standardized column names for readability.
* Corrected inconsistent spellings and unified data formats.
* Added derived features where needed.
* Separated features into:
  1. Categorical columns
  2. Continuous/numerical columns
  3. Target column: readiness_level
* Applied Yeo-Johnson transformation for continuous variables to handle skewness.
* Applied One-Hot Encoding for categorical variables.
* Built a preprocessing pipeline for clean separation of training and transformation steps.

**Exploratory Data Analysis (EDA):**

Performed detailed statistical and graphical analysis such as:
* Histograms, countplots, bar charts, and distribution plots.
* Correlation analysis between study habits, sleep, stress levels, and readiness.
* Insights on:
  1. Sleep vs fatigue
  2. Study intensity vs anxiety
  3. Time usage patterns vs confidence

**Statistical Tests:**

Used appropriate hypothesis tests to explore relationships:
1. Chi-Square Test for categorical relationships
(e.g., gender vs study intensity)

2. ANOVA for comparing group means
(e.g., study intensity vs readiness level)

**Machine Learning Model:**

* Built a KNN classification model to predict the readiness level.
* Constructed a full ML pipeline combining:
  1. Yeo-Johnson transformation
  2. One-Hot Encoding
  3. Scaling
  4. KNN classifier
Evaluated model performance using accuracy and classification metrics.

**Tech Stack:**

* Python
* Pandas, NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Scipy (statistical tests)
