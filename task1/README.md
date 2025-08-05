## Titanic Dataset – Data Cleaning & Preprocessing

This repository contains my submission for **Task 1** of the Internship Program, where I performed comprehensive **data cleaning and preprocessing** on the Titanic dataset.


### Dataset Source

The dataset used is the classic **Titanic survival dataset**, which contains passenger details such as age, sex, fare, class, and survival outcome.


### Files Included
      
  File Name	                               Description
Titanic-Dataset.csv              	Original raw dataset
Cleaned_Titanic_Dataset.csv	      Final cleaned dataset after preprocessing
task1.ipynb	                      Jupyter Notebook containing full step-by-step data cleaning
task 1.pdf	                      PDF containing task guidelines
task 1	                          README file summarizing Task 1


### Tools Used
-> Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
-> Jupyter Notebook


### Task Objectives
The primary goal was to prepare the dataset for machine learning by:
-> Handling missing values
-> Encoding categorical variables
-> Scaling numerical features
-> Removing outliers


### Steps Performed
#### 1. **Import & Explore**
-> Loaded the dataset using `pandas`
-> Checked data types, shape, and missing values
-> Explored summary statistics for all features

#### 2. **Handle Missing Values**
-> `Age`: Imputed with median
-> `Embarked`: Imputed with mode
-> `Cabin`: Dropped (77% missing)
-> `Name` and `Ticket`: Dropped as not useful for ML

#### 3. **Encode Categorical Features**
-> `Sex`: Label encoded (male → 0, female → 1)
-> `Embarked`: One-hot encoded (C, Q, S)

#### 4. **Normalize / Standardize**
-> Used `StandardScaler` to scale:
    - `Age`, `Fare`, `SibSp`, `Parch`

#### 5. **Detect & Remove Outliers**
->  Used **boxplots** and **IQR method** to detect outliers
->  Removed extreme values from key numerical columns


### Skills & Concepts Applied
-> Data Inspection & Summary Statistics
-> Null Value Imputation
-> Feature Dropping & Encoding
-> Data Type Conversion
-> Dataset Exporting
-> Git & GitHub


### Key Takeaways
-> Developed hands-on experience in cleaning real-world datasets
-> Understood common data quality issues like missing values and datatype mismatches
-> Learned how to preprocess a dataset in a reproducible, step-by-step manner


### Connect
Feel free to explore the repo and connect with me on [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/your-username) if you have any feedback, suggestions, or would like to collaborate!

