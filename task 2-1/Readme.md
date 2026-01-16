House Prediction Description :

Project Description :

This project focuses on data preprocessing and cleaning of a House Price dataset using Python.
The main objective is to analyze missing values, visualize data quality issues, and clean the dataset so it is ready for further analysis or predictive modeling.
This project follows standard data cleaning practices used in real-world data science and internship tasks.

Tools & Libraries Used :

Python
Pandas – data manipulation and cleaning.
NumPy – numerical operations.
Matplotlib – data visualization.

Dataset Information :

Original Dataset: Day3_House_Price_data (1).csv.
Cleaned Dataset: cleaned_house_price_data.csv.

Project Objectives :

Identify missing values in the dataset.
Visualize missing data patterns.
Apply appropriate techniques to handle missing values.
Remove columns with excessive missing data.
Save a cleaned and reliable dataset.

Step-by-Step Process :

Dataset Loading :

Loaded the dataset using pandas.read_csv().
Displayed the dataset shape before cleaning.

Missing Value Detection :

Calculated missing values for each column.
Displayed only columns containing missing values.
Calculated missing value percentage for better understanding.

 Missing Data Visualization :

Created a bar plot showing percentage of missing values per column.
Visualized which features require cleaning or removal.
Used Matplotlib for clear representation.

Column Type Identification :

Numerical Columns: int64, float64.
Categorical Columns: object.
Different strategies applied based on column type.

 Handling Missing Values : 

Numerical Columns :

Missing values replaced using the mean of the column.

Categorical Columns :

Missing values replaced using the most frequent value (mode).

Removing Columns with High Missing Values :

Defined a missing value threshold of 60%.
Columns exceeding this threshold were removed.
Ensures data quality and reliability.

Post-Cleaning Validation :

Verified total remaining missing values.
Displayed dataset shape after cleaning.
Ensured dataset is complete and usable.

Visual Output :

Bar chart showing missing value percentage per column.
Helps identify data quality issues quickly.