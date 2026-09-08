# House-price-prediction
House Price Prediction is a machine learning project that predicts house prices based on factors such as location, house size, number of bedrooms and bathrooms, house age, parking spaces, and distance from the city. The project uses data preprocessing, visualization, and Linear Regression to train and evaluate the prediction model.
# House Price Prediction

## Project Description

House Price Prediction is a machine learning project that predicts the price of a house using different property features such as location, house size, bedrooms, bathrooms, house age, parking spaces, and distance from the city.

## Objectives

* Analyze house price data
* Identify factors affecting house prices
* Clean and preprocess the dataset
* Visualize relationships between features and prices
* Build a machine learning model
* Predict house prices
* Evaluate model performance

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Machine Learning Algorithm

The project uses **Linear Regression** to predict house prices.

## Dataset Features

* property_id
* location
* house_size_sqft
* bedrooms
* bathrooms
* house_age_years
* parking_spaces
* distance_to_city_km
* price

The `price` column is the target variable.

## Data Preprocessing

The project handles missing values, standardizes numerical features, and converts the categorical location feature using one-hot encoding. The dataset is divided into training and testing sets.

## Model Evaluation

The model is evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

The project also predicts the price of a sample new house and identifies important factors affecting house prices.

## Visualizations

The project generates:

* House Size vs House Price
* Actual vs Predicted House Prices

## How to Run

1. Install Python.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
python house_price_prediction.py
```

## Note

The included dataset is synthetic and is intended for educational and machine learning practice.
