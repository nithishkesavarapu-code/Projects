# California Housing Price Prediction

## Project Overview
This project demonstrates a predictive analysis using a linear regression model to forecast median house values in California districts. The analysis is built using the well-known California Housing dataset from the scikit-learn library.

The main objective is to explore the dataset, build a linear model, and evaluate its performance in predicting housing prices based on several key features.

## Key Features
* **Data Loading & Exploration**: Uses pandas to load and inspect the California Housing dataset.
* **Data Cleaning**: Checks for and confirms the absence of missing values.
* **Model Training**: Implements a `LinearRegression` model from scikit-learn.
* **Model Evaluation**: Assesses the model's predictive power using standard regression metrics.
* **Visualization**: Creates a scatter plot to visually compare actual vs. predicted values.

## Dataset
The project utilizes the **California Housing** dataset, which contains data from the 1990 U.S. Census. Each row represents a single block group and includes the following features:
* `MedInc`: Median income in a block group.
* `HouseAge`: Median age of a house.
* `AveRooms`: Average number of rooms.
* `AveBedrms`: Average number of bedrooms.
* `Population`: Block group population.
* `AveOccup`: Average number of household members.
* `Latitude`: Latitude of the block group.
* `Longitude`: Longitude of the block group.

The model's target variable is `MedHouseVal`, which represents the median house value for California districts in hundreds of thousands of dollars ($100,000s).

## Requirements
To run this notebook, you need to have the following Python libraries installed:
* `pandas`
* `numpy`
* `matplotlib`
* `scikit-learn`
You can install these using pip:
```bash
pip install pandas numpy matplotlib scikit-learn
