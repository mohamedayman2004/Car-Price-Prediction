# Car Price Prediction Model

This project is a machine learning model designed to predict the selling price of cars based on various features such as year, present price, kilometers driven, fuel type, selling type, transmission, and owner history.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The goal of this project is to build a predictive model that estimates the selling price of a car using machine learning techniques. The model is trained on a dataset containing various attributes of cars, and it uses a **Random Forest Regressor** to make predictions.

## Dataset
The dataset used in this project contains the following columns:
- `Car_Name`: Name of the car.
- `Year`: Manufacturing year of the car.
- `Selling_Price`: The target variable, representing the selling price of the car.
- `Present_Price`: The current showroom price of the car.
- `Driven_kms`: Total kilometers driven by the car.
- `Fuel_Type`: Type of fuel the car uses (Petrol, Diesel, CNG).
- `Selling_type`: Type of seller (Dealer or Individual).
- `Transmission`: Transmission type (Manual or Automatic).
- `Owner`: Number of previous owners.

The dataset is provided in a CSV file named `car data.csv`.

## Features
- **Data Preprocessing**: Handles missing values, encodes categorical variables, and scales numerical features.
- **Model Training**: Uses a Random Forest Regressor to predict car prices.
- **Model Evaluation**: Evaluates the model using Mean Squared Error (MSE) and R² Score.
- **Fine-Tuning**: Optional hyperparameter tuning using Grid Search.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/mohamedayman2004/car-price-prediction.git
   cd car-price-prediction
