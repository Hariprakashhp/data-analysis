# data-analysis

# Overview
The notebook covers the following steps:

1. Data Loading and Inspection
Loading Data: The dataset is loaded from a CSV file named train.csv.
Dataset Overview: It provides an overview of the dataset, including its shape (number of rows and columns) and basic statistics for numerical features.
2. Data Cleaning
# Missing Values: The notebook checks for missing values in the dataset.
Duplicates: It identifies and removes any duplicate rows to ensure data quality.
3. Statistical Summary
Feature Statistics: Detailed statistics are generated for various features, such as mean, standard deviation, and percentiles.
Outlier Detection: The notebook calculates the interquartile range (IQR) and identifies upper and lower bounds for certain features to detect outliers.
4. Visualizations
# Age Analysis:
A boxplot is created to show the distribution of ages in the dataset.
A distribution plot is used to illustrate the frequency distribution of the age feature.
# Job Analysis:
A countplot and barplot are generated to visualize the distribution of different job types.
# Marital Status Analysis:
Similar countplot and barplot visualizations are provided for marital status.
Education Qualification Analysis:
Countplot and barplot are used to explore the distribution of education qualifications.
Education qualifications are mapped to numerical values for easier analysis.
# Month Analysis:
A countplot and barplot visualize the distribution of months.
Deprecated Warnings
Note that some functions used in the notebook, like distplot, are deprecated and will be removed in future versions of the Seaborn library. Alternative functions such as displot or histplot are recommended.
Prerequisites
Make sure you have the following Python libraries installed:

pandas
numpy
matplotlib
seaborn
