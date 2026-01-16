# task-2-
Explain data analysis on house prediction and medical appointment dataset
Project Description :

This project demonstrates end-to-end data cleaning, missing value analysis, and preprocessing on two real-world datasets using Python.
The datasets include Medical Appointment data and House Price data, both cleaned using industry-standard data science practices.
The objective is to transform raw datasets into clean, reliable, and analysis-ready data suitable for exploratory data analysis and machine learning tasks.

 Tools & Libraries Used : 

Python
Pandas
NumPy
Matplotlib

Datasets Used : 

Dataset	Original File	Cleaned File
Medical Appointment	medical appointment dataset.csv	cleaned_medical_appointment_dataset.csv
House Price	Day3_House_Price_data (1).csv	cleaned_house_price_data.csv.
 
Project Objectives :

Load and inspect real-world datasets.
Identify missing values and data quality issues.
Visualize missing data patterns.
Apply appropriate cleaning strategies.
Remove low-quality columns.
Save cleaned datasets for further analysis.

Data Cleaning Workflow :

 Dataset Loading : 

Datasets loaded using pandas.read_csv().
Initial dataset shapes printed to understand data size.
 
 Initial Data Inspection :

Displayed first and last rows.
Checked column names and data types.
Verified dataset dimensions before cleaning.

Missing Value Analysis : 

Calculated missing values per column.
Computed missing value percentages.
Displayed only columns containing missing data.

 Missing Data Visualization :

Bar charts used to visualize :

Missing value counts.
Missing value percentages per column.
Helped identify problematic features.

 Column Classification :

Numerical Columns: int64, float64
Categorical Columns: object
Different cleaning strategies applied based on column type.

 Handling Missing Values :

Medical Appointment Dataset :
 
Numerical columns → filled using median.
Categorical columns → filled using mode.
Columns with more than 50% missing values removed.

House Price Dataset :

Numerical columns → filled using mean.
Categorical columns → filled using mode.
Columns with more than 60% missing values removed.

 Post-Cleaning Validation :

Verified remaining missing values.
Compared dataset shape before and after cleaning.
Checked dataset info and statistical summary.

Saving Cleaned Data :

Cleaned datasets saved as CSV files.

Ready for :

Exploratory Data Analysis (EDA)
Feature Engineering
Predictive Modeling

 Visual Outputs :

Missing value distribution plots.
Missing value percentage bar charts.
Data quality inspection visuals.

 Final Outcome :

Two clean, structured, and reliable datasets.
Reduced noise caused by missing data.
Improved dataset usability.
Prepared for real-world data science workflows.
