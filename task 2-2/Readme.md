Medical Appointment description : 

Project Description :

This project demonstrates data cleaning and exploratory analysis on a Medical Appointment dataset using Python.
The objective is to handle missing values, understand data structure, and prepare a clean dataset for further analysis or machine learning tasks.

Tools & Libraries :

Python
Pandas
NumPy
Matplotlib

Dataset Details :

Input File: medical appointment dataset.csv
Output File: cleaned_medical_appointment_dataset.csv

Steps :

Dataset Loading :

Loaded dataset using pandas.read_csv()
Displayed confirmation message after loading

 Initial Exploration :

Displayed first 5 rows
Displayed last 5 rows
Checked dataset shape before cleaning

 Missing Value Analysis :

Calculated missing values for each column
Visualized missing values using bar charts
Checked whether missing values exist before plotting

 Column Classification :

Identified numerical columns (int64, float64)
Identified categorical columns (object)

Handling Missing Values :

Numerical columns filled with median
Categorical columns filled with mode
Columns with more than 50% missing values removed

 Post-Cleaning Validation :

Verified remaining missing values
Checked dataset shape after cleaning
Displayed dataset info (df.info())
Generated statistical summary (df.describe())

Visualizations :

Missing value distribution before cleaning
Column-wise missing value bar plots
