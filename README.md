# Big-Data-Project-Using-Spark

## Dataset:

Datset comprises of 48,842 number of records with around 15 attributes. 

Source: https://archive.ics.uci.edu/ml/datasets/Census+Income

## Project Overview:
 - Descriptive Analytics 
Perform Exploratory Analysis of Census Income data with an aim to find statistical distribution of different socio-economic factors.

- Predictive Analytics
Predict whether a person would earn more than 50k annually based on socio- economic factors such as education, age, race, etc.


## Description

**There exists seperate script file for each step**

**Instructions to run the project**
1. Load the clean.csv file to S3 data.
2. Perform exploratory data analysis using AWS Quicksight.
3. Use the Link_to_S3.json to connect to S3 file.
5. Create a cluster and choose pig by clicking on advance options
4. Use the census_cleaning.pig file to clean the dataset.
5. Put the clean data in Hive
6. Output of hive file is a structured csv
7. Place the CSV back in S3 bucked.
8. Run ML models on it using Pyspark

## Result & Model Summaries

| Model | Accuracy | 
|---|---|
| Logistic Regression | 87.49% |
| Randome Forest | 85.54% | 
| Support Vector Machine  |86.39%| 
|Gradient Boosting | 87.89% |




