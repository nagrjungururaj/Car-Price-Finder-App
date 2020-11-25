# Car-Price-Finder
Predicts price of your current car to be sold

# About the model
Feature selction using random forests is done to find feature importances  
Uses an elastic regression model to predict the price of cars using the feature columns of "car data.csv"

# Model API
The solutions uses Flask, HTML and CSS to generate the API and local web app

# Deploying the model
The trained model flask app is deployed on Heroku platform. 

# Accesing the application
Click here: https://elastic-car-price-prediction.herokuapp.com/  



## Form Fields
Owner-Type : First Owner 0, Second Owner 1  
Diesel : If fuel type diesel 1; else 0  
Petrol : If fuel type petrol 1; else 0  
Seller_type : 1 if individual 0 if dealer
Transmission : 1 if manual 0 if automatic
