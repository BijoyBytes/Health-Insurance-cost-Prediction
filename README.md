

# Health Insurance Cost Prediction✅📈

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## Overview
This project aims to predict insurance costs using machine learning techniques. The dataset used contains information about the insured individuals and their respective charges. By analyzing these data points, the model can predict future insurance costs based on new inputs.

<img align="right" alt="Coding" width="400" src="https://media.istockphoto.com/vectors/health-insurance-icon-logo-vector-graphic-design-hands-and-red-cross-vector-id1029378270?k=6&m=1029378270&s=170667a&w=0&h=ZtXSIngZaI92T8bqka1adP3GJWhdMbfbCGtk0buGyzQ=">


## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Data](#data)
- [Analysis](#analysis)
- [Learning](#learning)
- [Acknowledgements](#acknowledgements)

## Introduction
Predicting insurance costs is essential for insurance companies to accurately estimate potential expenses and determine appropriate premiums. This project uses a dataset containing demographic information including age, sex, BMI, number of children, smoking status, and region to forecast insurance charges.

- **Project Objective:**

   **1.** Create a Prediction model that can predict  _[Health insurance cost](https://github.com/graphical-Analysis/Health-Insurance-cost-Prediction/blob/main/Health%20Insurance%20cost%20Prediction.ipynb)_ 

Create a model that can predict the cost of health insurance based on ['age', 'sex', 'bmi', 'children', 'smoker', 'region', 'charges'] parameter
Observation:

## Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Hyperparameter tuning
- Model deployment using Flask (optional)

## Data
The dataset used in this project can be found [here](https://www.kaggle.com/mirichoi0218/insurance). It contains the following columns:
- `age`: Age of the primary beneficiary
- `sex`: Gender of the beneficiary (male/female)
- `BMI`: Body Mass Index
- `children`: Number of children/dependents covered by health insurance
- `smoker`: Smoking status (yes/no)
- `region`: Residential area in the US (northeast, southeast, southwest, northwest)
- `charges`: Individual medical costs billed by health insurance

## Analysis

- **1. In this data, we have 7 columns which are:**
  
['age', 'sex', 'BMI', 'children', 'smoker', 'region', 'charges']

Numerical columns in the data:['age', 'BMI', 'children', 'charges']

Categorical columns in the data:['sex', 'smoker', 'region']

- **2. Male and Female count**
  
sex male(1) 675
female(0) 662

There are 675 Males and 662 Females Here Males are denoted by "1" and Females are denoted by "0"

- **3.% of children's distribution**
  


| Children| %    |
| :-------- | :------- |
| 0 | `42.86%` |
| 1 | `24.23%` |
| 2 | `17.95%` |
| 3 | `11.74%` |
| 4 | `1.87%` |
| 5 | `1.35%` |


In our data set, among those who have taken insurance 42% people have no child, 24% people only have only one child, 17% people have two children, 11% people have 3 children

- **4.Charges Distibution**

  
Most of the insurance costs in our data set are between 0 to 10000

- **5.Region wise distibution**
  
In the data set contains 4 types of regions which are "Southeast", "Southwest", "Northeast","Northwest" but the amount of "south-east" regions is high as compared to the other areas and also the cost of insurance is high in "south-east" region

| Region | Charges    |
| :-------- | :------- |
| northeast(0) | `13406.384516` |
| northwest(1) | `12450.840844` |
| southeast(2) | `14735.411438` |
| southwest(3) | `12346.937377` |


- **6. Insurance costs for smokers and non-smokers**
  
In the case of smokers, the insurance cost is so high and non-smokers have lower insurance rates although in our data set the number of non-smokers is high

smoker 

no (0) 1063

yes (1) 274 

Here non-smokers are denoted by "0" and smokers are denoted by "1"

- **7. Create a Prediction model**
  
I have used a "LinearRegression()" model to predict our data. At first, I split my data into training and testing. I used 80% of our data for training and the remaining 20% for testing

Then I try to predict as a user input that is

age=21, sex= 0(Female), bmi=25.8000, children= 0, smoker=0(non-smoaker"), region=3("southwest")

ans=model.predict([[21,0,25.800,0,0,3]]) print("your Insurance cost is", ans)

Your insurance cost is [1528.79685196]


model.score(x_test,y_test) 0.8068466322629112

### Model accuracy is 80%

## Learning:
- [x]	Proficiency in ETL methodology (Extract, Transform, Load).
- [x]	Data cleaning and preprocessing
- [x]	Business Understanding


## Acknowledgements

 - The dataset used in this project is sourced from [Kaggle.](https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance)
 - This project is inspired by various machine learning tutorials and courses available on YouTube[.]()







