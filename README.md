# 🚗 Car Price Prediction Using Linear Regression

This project is a Machine Learning based web application that predicts the resale price of a used car based on its details such as company, model, year, kilometers driven, and fuel type.

## 📌 Project Overview

The main objective of this project is to predict the estimated price of a used car using a Linear Regression model. The dataset used in this project is based on Quikr car data.

## 📂 Dataset

Dataset Name: `quikr_car.csv`

The dataset contains the following columns:

- `name` - Car model name
- `company` - Car company/brand
- `year` - Year of purchase
- `Price` - Selling price of the car
- `kms_driven` - Total kilometers driven
- `fuel_type` - Type of fuel used by the car

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Linear Regression
- Flask
- HTML
- CSS
- Bootstrap
- JavaScript

## 🔄 Project Workflow

1. Loaded the Quikr car dataset.
2. Cleaned the dataset by handling unwanted values and formatting issues.
3. Converted price, year, and kilometers driven into proper numeric format.
4. Removed missing and invalid records.
5. Save dataset Cleaned car.csv
6. Trained a Linear Regression model.
7. Saved the trained model using Pickle.
8. Created a Flask web application.
9. Designed an attractive user interface using HTML, CSS, and Bootstrap.
10. Predicted car prices based on user input.

## 🤖 Machine Learning Model

The model used in this project is:

**Linear Regression**

Linear Regression is used to find the relationship between car features and the selling price. It predicts the car price based on input values provided by the user.

## 🌐 Web Application Features

- Select car company
- Select car model
- Select purchase year
- Select fuel type
- Enter kilometers driven
- Predict estimated car price instantly

## 📁 Project Structure

```bash
Car-Price-Prediction-Using-Linear-Regression/
│
├── application.py
├── LinearRegreession.pkl
├── cleaned car.csv
├── quikr_car.csv
│
├── templates/
│   └── index.html
│
├── static/
│   └── css/
│       └── style.css
│
└── README.md
