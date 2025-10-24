# Data-Cleaning-on-Titanic-Dataset

This project focuses on cleaning and preparing the Titanic dataset for further data analysis and visualization.
The dataset contains information about passengers on the Titanic — such as age, gender, ticket class, and survival status.

The main objective is to:

Identify and handle missing data

Fix data inconsistencies

Encode categorical variables

Save a clean dataset for future EDA or modeling

**#Tools & Libraries Used**

Python

Pandas

NumPy

Google Colab / Jupyter Notebook

**Steps Performed**

Data Loading: Imported the dataset using pandas

Exploration: Checked data types, shape, and missing values

Cleaning:

Filled missing Age with median

Filled missing Embarked with mode

Dropped the Cabin column (too many missing values)

Removed duplicate rows

Encoding:

Converted Sex into numeric (0 = male, 1 = female)

One-hot encoded the Embarked column

Exported Cleaned Dataset: Saved as titanic_cleaned.csv

**Insights**

Around 20% of Age values were missing

The majority of passengers embarked from Southampton (S)

The Cabin column was mostly empty and dropped

After cleaning, the dataset is ready for EDA and machine learning
