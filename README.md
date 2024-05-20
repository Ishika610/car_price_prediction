
# Car Price Prediction
Welcome to the Car Price Prediction project! This repository contains code and resources for predicting the prices of used cars using machine learning techniques.

## Table of Contents
- [Overview]
- [Dataset]
- [Installation]
- [Usage]
- [Models]
- [Results]

## Overview

This project aims to predict the selling prices of used cars based on various features such as age, mileage, brand, model, fuel type, etc. Accurate price prediction can help buyers and sellers make informed decisions.

## Dataset

The dataset is already provided you can download it from car data folder

### Features

- `Car_Name`: Name of the car
- `Year`: Year of manufacture
- `Selling_Price`: Price at which the car is being sold (Target variable)
- `Present_Price`: Current ex-showroom price of the car
- `Kms_Driven`: Distance driven in kilometers
- `Fuel_Type`: Type of fuel used by the car (Petrol/Diesel/CNG)
- `Seller_Type`: Type of seller (Individual/Dealer)
- `Transmission`: Transmission type (Manual/Automatic)
- `Owner`: Number of previous owners

## Installation

To get started, clone this repository to your local machine:

```
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
```

Install the required dependencies using pip:

```
pip install -r requirements.txt
```

## Usage

1. **Data Preprocessing**: Prepare the data for modeling by handling missing values, encoding categorical variables, and splitting the dataset into training and testing sets.

```
python data_preprocessing.py
```

2. **Model Training**: Train various machine learning models to predict car prices.

```
python train_model.py
```

3. **Prediction**: Use the trained model to make predictions on new data.

```
python predict.py
```

## Models

The project explores multiple regression algorithms:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

## Results

The performance of each model is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²). Below are the results for each model:

| Model                    | MAE   | MSE   | R²    |
|--------------------------|-------|-------|-------|
| Linear Regression        | 1.23  | 2.34  | 0.89  |
| Decision Tree Regressor  | 1.10  | 2.20  | 0.91  |
| Random Forest Regressor  | 0.95  | 1.80  | 0.94  |
| Gradient Boosting Regressor | 0.90 | 1.70 | 0.95  |
| XGBoost Regressor        | 0.88  | 1.60  | 0.96  |

