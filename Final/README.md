Project Name: Machine Learning - Airbnb Prices

Carlee Peterson and MeKenzi Bogard

Problem Statement: What features correlate to Airbnb prices?

We are attempting to create a Machine Learning model to predict prices for Airbnb within the individual Portland, OR neighborhoods. 

The datasets we will be using are from Inside AirBnB, which is a public project providing data that quantifies the impact of short-term rentals on housing and residential communities. These include .csv files with listing information that include features such as price, room type, id, etc. 

Inside Airbnb: http://insideairbnb.com/get-the-data.html

For tools and packages, we will be utilizing Jupyter Notebook for the programming, and several python packages.

Packages include:
- Python=3.8
- geopandas
- matplotlib
- numpy
- jupyter
- scikit 

The planned methodology we'll be using for our approach is based on the Lab 5, where  we will train a machine learning model using scikit-learn to engineer some features for better prediction of AirBnB prices in Portland, OR. We will be using the RandomForests regressor for our prediction model. Unlike Lab 5, we will be going a step further to create a model for each individual neighborhood rather than the entire dataset of Airbnbs.

The expected outcome for this project is that using multiple models for the individual neighborhoods will produce lower (better) error outcomes for the model.

Our reference for this final project include Lab 5 and the Airbnb metadata: https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=982310896
