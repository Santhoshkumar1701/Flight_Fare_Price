# Flight Fare Price Prediction Web App

This s is a web application built using Flask and machine learning (Random Forest) to predict flight prices based on various input parameters such as travel date, departure time, arrival time, number of stops, airline, source, and destination.


![Flight Price](https://github.com/Santhoshkumar1701/Flight_Fare_Price/assets/110801787/0c758fa0-6da9-4467-b56e-5c8b9123405a)


## Features

* User-friendly web interface for inputting flight details.
* Utilizes a trained Random Forest model to predict flight prices.
* Support for selecting various airlines, sources, and destinations.
* Clear prediction results are displayed to the user.
* Getting Started

## Prerequisites
* Python 3.7 or higher 
* Flask
* pandas
* scikit-learn
* pickle 
* Installation 
## Dataset
* The dataset used for this project contains flight price information for various flights. It was collected from reliable sources and consists of the following features:

* Date of Journey: Date and time of flight departure.
* Airline: The airline operating the flight.
* Source: Departure city of the flight.
* Destination: Arrival city of the flight.
* Dep_Time: Departure time.
* Arrival_Time: Arrival time.
* Duration: Duration of the flight.
* Total_Stops: Number of stops during the flight.
* Price: The target variable we aim to predict - flight fare.

## Web Application with HTML, CSS, and Flask
This project involves building a Flight Price Prediction web application using a combination of HTML, CSS, and the Flask framework. The project follows these key steps:

## 1. Frontend Design (HTML and CSS):
* The user interface of the web application is designed using HTML for structure and CSS for styling. The user-friendly interface includes input forms for users to enter flight details such as departure time, arrival time, airline, source, and destination.

## 2. Flask Backend:
* The backend of the application is powered by Flask, a Python web framework. Flask handles routing, request processing, and response generation. The application has two main routes: the home route ("/") to display the user interface and the prediction route ("/predict") to handle user inputs and return predicted flight prices.

Machine Learning Model Integration:
The project incorporates a machine learning model, specifically a Random Forest regressor, which predicts flight prices based on input features. The trained model is loaded into the Flask application and utilized in the prediction route to provide accurate fare estimates.

