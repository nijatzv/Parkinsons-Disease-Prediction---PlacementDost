# Parkinson's Disease Prediction

This repository contains a Jupyter notebook for predicting Parkinson's Disease using machine learning. The notebook includes data preprocessing, exploratory data analysis (EDA), model training, and prediction steps.

## Table of Contents
- [Introduction](#introduction)
- [Setup](#setup)
- [Data](#data)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training](#model-training)
- [Prediction](#prediction)
- [Results](#results)
- [Usage](#usage)
- [License](#license)

## Introduction
The goal of this project is to build a machine learning model that can predict whether a person has Parkinson's Disease based on various features. The dataset used for this project is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/parkinsons).

## Setup
To run this notebook, you need to have Python and Jupyter Notebook installed on your machine. You can install the required packages using `pip`:


Here's a sample README.md file for your GitHub repository, including instructions on how to run the notebook and a section for the correlation heatmap image.

README.md
markdown
Copy code
# Parkinson's Disease Prediction

This repository contains a Jupyter notebook for predicting Parkinson's Disease using machine learning. The notebook includes data preprocessing, exploratory data analysis (EDA), model training, and prediction steps.

## Table of Contents
- [Introduction](#introduction)
- [Setup](#setup)
- [Data](#data)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training](#model-training)
- [Prediction](#prediction)
- [Results](#results)
- [Usage](#usage)
- [License](#license)

## Introduction
The goal of this project is to build a machine learning model that can predict whether a person has Parkinson's Disease based on various features. The dataset used for this project is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/parkinsons).

## Setup
To run this notebook, you need to have Python and Jupyter Notebook installed on your machine. You can install the required packages using `pip`:

## Data
The dataset used in this project is included in the repository. It contains multiple features related to voice measurements that are used to detect Parkinson's Disease.

## Exploratory Data Analysis
EDA is performed to understand the dataset better and to identify any patterns or relationships between features. Below is the correlation heatmap for the features:
<img alt="Correlation Heatmap" src="C:\Users\Lenovo\Desktop\correlation.png">

## Model Training
Several machine learning models are trained and evaluated to find the best model for predicting Parkinson's Disease. The models include:

* Logistic Regression
* Random Forest
* Support Vector Machine

## Prediction
The final model is used to make predictions on new data. The notebook includes code for preprocessing input data, scaling features, and making predictions using the trained model.

## Results
The performance of the models is evaluated using various metrics such as accuracy, precision, recall, and F1-score. The best model is selected based on these metrics.

```bash
pip install -r requirements.txt
