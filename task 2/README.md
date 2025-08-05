## Titanic Dataset – Exploratory Data Analysis (EDA)
This repository contains my submission for Task 2 of the Internship Program, where I performed Exploratory Data Analysis (EDA) on the Titanic dataset using various visualizations to understand patterns, relationships, and distributions in the data.


### Dataset Source
The dataset used is the Cleaned Titanic survival dataset, containing information about passengers including age, sex, fare, class, family size, and survival status, cleaned as the result of Task 1.


### Files Included
File Name	                               Description
Cleaned-Titanic-Dataset.csv	      Cleaned Original dataset
task2_EDA.ipynb	                  Jupyter Notebook containing all EDA code & visuals
task 2.pdf	                      PDF containing task instructions
task 2 README.md	                This README summarizing Task 2


### Tools & Libraries Used
-> Python (Pandas, NumPy, Matplotlib, Seaborn)
-> Jupyter Notebook


### Task Objectives
-> The main goal of this task was to:
-> Explore the dataset visually
-> Identify patterns, trends, and outliers
-> Understand the distribution of key variables
-> Generate insights for future modeling tasks


### Steps Performed
1. Initial Exploration
Loaded dataset and checked basic info (shape, columns, nulls)
Displayed statistical summary and data types

2. Univariate Analysis
Used boxplots and histograms to analyze:
      Survival Distribution
      Passenger Class (Pclass)
      Sex
      Embarked Port
      Fare Distribution
      Age Distribution

3. Trends & Patterns Observed
Feature	Pattern/Trend	Inference
Pclass vs Survival	Higher survival in 1st class	First-class passengers may have had better access to lifeboats
Sex vs Survival	Females had much higher survival rates	"Women and children first" rescue policy followed
Embarked vs Survival	Highest survival from Cherbourg	Possibly more 1st class passengers boarded at this port
Fare vs Survival	Higher fares correlated with higher survival	High fare likely meant 1st class
Age vs Survival	Survivors slightly skewed younger, not strictly linear	Children possibly prioritized
SibSp/Parch vs Survival	Passengers with small families had higher survival	Small family units may have coordinated better during evacuation

4. Anomalies Detected
Using boxplots and IQR method, the following anomalies were identified:
Fare:
    Outliers detected: fares above 300 were extremely rare
    Possible luxury cabins or group bookings
Age:
    Outliers: Some passengers over 70 years old
    Might indicate wealthy elders traveling with family
SibSp/Parch:
    Passengers with 5–6 siblings/spouses or parents/children
    These were rare and had lower survival rates


### Key Visuals Created
-> Boxplots  for fare and age distribution and histograms
-> Heatmaps for correlation checks


### Skills & Concepts Applied
-> Exploratory Data Analysis (EDA)
-> Data Visualization using Seaborn & Matplotlib
-> Feature Distribution Analysis
-> Pattern Recognition from Visuals
-> Insight Generation for ML Readiness

### Takeaways
-> Gained deeper understanding of data visualization best practices
-> Learned how to derive inferences from visual patterns
-> Identified important features influencing survival
-> Set a strong foundation for the upcoming predictive modeling task

### Connect
Feel free to explore the repo and connect with me on [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/your-username) if you have any feedback, suggestions, or would like to collaborate!







if you have any feedback, ideas, or would like to collaborate!
