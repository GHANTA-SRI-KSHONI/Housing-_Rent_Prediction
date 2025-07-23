# Housing-_Rent_Prediction
House Rent Prediction
This project predicts house rent prices based on various features of the property. It uses a Random Forest Regressor model to make the predictions.

Project Overview
The goal of this project is to build a machine learning model that can accurately predict the rent of a house given its features. The model is trained on the "House_Rent_Dataset.csv" dataset, which contains information about various properties, including:

BHK: Number of bedrooms, hall, and kitchen.
Size: Size of the house in square feet.
Floor: The floor of the apartment and the total number of floors in the building.
Area Type: The type of area (e.g., Super Area, Carpet Area).
City: The city where the property is located.
Furnishing Status: Whether the house is furnished, semi-furnished, or unfurnished.
Tenant Preferred: The preferred type of tenant (e.g., Bachelors, Family).
Bathroom: The number of bathrooms.
Point of Contact: The point of contact for renting the property.
Steps Involved
Data Loading and Cleaning: The dataset is loaded using pandas and any missing values are dropped.
Feature Engineering: The relevant features are selected, and categorical features are converted into numerical features using one-hot encoding.
Model Training: The data is split into training and testing sets, and a Random Forest Regressor model is trained on the training data.
Model Evaluation: The model is evaluated on the testing data using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
Model Saving: The trained model is saved using joblib for future use.
Prediction: A function is created to predict the rent of a new property given its features.
