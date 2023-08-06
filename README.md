# Car Price Prediction using CarDekho Dataset

![Car Image](images/Car%20image.jpeg)



This project aims to predict car prices using the CarDekho dataset. CarDekho is a well-known platform for buying and selling cars, and this project leverages machine learning techniques to develop a predictive model that estimates the price of used cars based on various features.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Preparation](#data-preparation)
- [Train-Test Split](#train-test-split)
- [Model Creation and Evaluation](#model-creation-and-evaluation)
  - [Linear Regression](#linear-regression)
  - [Ridge](#ridge)
  - [Lasso](#lasso)
  - [Random Forest](#random-forest)
  - [Gradient Boosting](#gradient-boosting)
- [Results](#results)

## Introduction

The primary objective of this project is to build a machine learning model that can predict the selling price of used cars based on a set of features. By utilizing historical data from the CarDekho dataset, we seek to develop accurate and reliable price predictions, which can assist both buyers and sellers in making informed decisions.

## Dataset

The dataset used for this project is sourced from CarDekho and includes information about various cars, such as their specifications and selling prices. The dataset encompasses features like:

- Fuel type
- Seller type
- Transmission
- Number of previous owners
- Present price
- Kilometers driven
- Car age
- And more...

## Installation

1. Clone this repository to your local machine:

```
git clone https://github.com/your-username/car-price-prediction.git
```

2. Navigate to the project directory:

```
cd car-price-prediction
```

3. Install the required Python packages:

```
pip install -r requirements.txt
```

## Usage

1. Ensure you have the necessary dataset file, `car data.csv`, in the `input` directory.

2. Run the Python script to perform car price prediction and model evaluation:

```
python car_price_prediction.py
```

## Data Preprocessing

The dataset is preprocessed to handle missing values and categorical features. Feature engineering is performed to create new informative variables, such as the age of the car. Categorical variables are transformed into numerical format using one-hot encoding.

## Exploratory Data Analysis (EDA)

Exploratory data analysis is conducted to understand the distribution of various features and their relationships with the target variable. Visualizations, such as histograms, box plots, and heatmaps, are used to gain insights into the data.

## Data Preparation

Categorical features are transformed into binary variables using one-hot encoding. The target variable (`Selling_Price(lacs)`) is separated from the feature set for model training.

## Train-Test Split

The dataset is split into training and testing subsets using an 80-20 ratio. The feature matrix (`X`) and the target variable (`y`) are prepared for training and evaluating the models.

## Model Creation and Evaluation

Several regression models are applied to predict car prices:
- Linear Regression
- Ridge
- Lasso
- Random Forest
- Gradient Boosting

Each model's performance is evaluated using metrics such as R-squared (R2) scores for training and testing, as well as cross-validation scores. Residual plots and scatter plots are used to visualize the model's performance.

## Results

The results of the model evaluation are presented in a tabular format, comparing R2 scores and cross-validation scores for each regression technique. These scores provide insights into the accuracy and generalization of the models in predicting car prices.


