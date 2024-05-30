

# Insurance Cost Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## Overview
This project aims to predict insurance costs using machine learning techniques. The dataset used contains information about the insured individuals and their respective charges. By analyzing these data points, the model can predict future insurance costs based on new inputs.

<img align="right" alt="Coding" width="400" src="https://media.istockphoto.com/vectors/health-insurance-icon-logo-vector-graphic-design-hands-and-red-cross-vector-id1029378270?k=6&m=1029378270&s=170667a&w=0&h=ZtXSIngZaI92T8bqka1adP3GJWhdMbfbCGtk0buGyzQ=">


## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Predicting insurance costs is essential for insurance companies to accurately estimate potential expenses and determine appropriate premiums. This project uses a dataset containing demographic information including age, sex, BMI, number of children, smoking status, and region to forecast insurance charges.

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
- `bmi`: Body Mass Index
- `children`: Number of children/dependents covered by health insurance
- `smoker`: Smoking status (yes/no)
- `region`: Residential area in the US (northeast, southeast, southwest, northwest)
- `charges`: Individual medical costs billed by health insurance

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/insurance-cost-prediction.git
    cd insurance-cost-prediction
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Data Preprocessing and Exploration**:
    ```python
    python data_preprocessing.py
    ```

2. **Model Training**:
    ```python
    python train_model.py
    ```

3. **Model Evaluation**:
    ```python
    python evaluate_model.py
    ```

4. **Prediction**:
    You can use the `predict.py` script to make predictions on new data:
    ```python
    python predict.py --input data/new_data.csv --output results/predictions.csv
    ```

## Project Structure



## Acknowledgements

 - The dataset used in this project is sourced from [Kaggle.](https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance)
 - This project is inspired by various machine learning tutorials and courses available on YouTube[.]()

