# Week 1 Data Science Project

## Data Acquisition, Cleaning and Exploratory Data Analysis

This project demonstrates the basic data preparation workflow used in a data science project.

The Titanic dataset was used as a publicly available dataset for data acquisition, cleaning, preprocessing, and exploratory data analysis.

## Objectives

- Acquire a publicly available dataset
- Inspect the dataset
- Identify missing values and duplicate records
- Clean and preprocess the data
- Perform exploratory data analysis
- Create meaningful visualizations
- Identify important patterns and insights

## Dataset

Dataset: Titanic Dataset

Initial dataset:
- 891 records
- 12 columns

After cleaning:
- 891 records
- 11 columns
- 0 missing values
- 0 duplicate records

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning

The following preprocessing steps were performed:

1. Missing Age values were replaced using the median.
2. Missing Embarked values were replaced using the mode.
3. The Cabin column was removed because a large proportion of its values were missing.
4. Duplicate records were checked.
5. Data types were examined.

## Exploratory Data Analysis

The following analyses were performed:

- Overall survival analysis
- Gender-wise survival analysis
- Passenger class analysis
- Age analysis
- Fare analysis
- Correlation analysis

## Visualizations

The project includes:

- Passenger survival distribution
- Survival by gender
- Survival by passenger class
- Age distribution
- Correlation heatmap
- Age vs Fare scatter plot

## Project Structure

Week1_DataScience_Project/

- dataset/
  - raw/
  - cleaned/
- notebooks/
- visualizations/
- documentation/
- README.md