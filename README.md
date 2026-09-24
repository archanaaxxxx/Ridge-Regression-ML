# EV Car Price Prediction using Ridge Regression

## Project Overview

This project predicts the **price of electric vehicles (EVs) in India** using **Ridge Regression**. The model uses vehicle features such as brand, model, range, power, and battery capacity to predict the price.

## Dataset

The dataset contains information about **26 electric cars** available in India.

### Features

* **Brand** – Brand name of the electric car
* **Model** – Model name of the car
* **Price** – Price of the electric car
* **Range** – Driving range of the car
* **Power** – Power of the vehicle
* **Battery** – Battery capacity

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning Algorithm

### Ridge Regression

Ridge Regression is a linear regression algorithm that uses regularization to reduce overfitting. Different alpha values are tested to evaluate the model performance.

The alpha values used are:

* 0.01
* 0.1
* 1
* 10
* 100

## Data Preprocessing

The following preprocessing steps are performed:

1. Separate the target variable **Price** from the input features.
2. Categorical features such as **Brand** and **Model** are encoded using One-Hot Encoding.
3. Numerical features such as **Range, Power, and Battery** are standardized using StandardScaler.
4. The dataset is divided into training and testing sets using an **80:20 split**.

## Model Evaluation

The model is evaluated using the following metrics:

* **MAE (Mean Absolute Error)** – Measures the average prediction error.
* **RMSE (Root Mean Squared Error)** – Measures the square root of the average squared prediction error.
* **R² Score** – Measures how well the model explains the variation in car prices.

Both training and testing performance are calculated.

## Project Workflow

```text
Load Dataset
     ↓
Explore Dataset
     ↓
Separate Features and Target
     ↓
Preprocess Categorical & Numerical Data
     ↓
Split Dataset into Train and Test
     ↓
Apply Ridge Regression
     ↓
Test Different Alpha Values
     ↓
Make Predictions
     ↓
Evaluate Model Performance
```

## Results

The Ridge Regression model is evaluated for different regularization values using:

* Train MAE
* Train RMSE
* Train R²
* Test MAE
* Test RMSE
* Test R²

The results are stored in a DataFrame for comparison.

## Conclusion

This project demonstrates how **Ridge Regression** can be used to predict electric vehicle prices based on their specifications. The use of preprocessing, feature encoding, scaling, and regularization helps build a machine learning pipeline for EV price prediction.

## Files

```text
Ridge_Regression.ipynb
ev_car_India_dataset.csv
README.md
```

## Author

**Archana Devi**
