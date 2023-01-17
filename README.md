# Andreea_Portfolio

## About me 
Hi! My name is Andreea.  
I am a tech enthusiast who wants to learn more and devolep her skills.
Please check below some projects I worked on.

## [Project 1: Who will purchase?](https://github.com/andreeamariacovaciu/Who-will-purchase)
The purpose of this project is to predict whether a customer would make a purchase or not based on three independent variables (Gender, Age, Salary) using KNN algorithm.  
For a better accuracy result I determined the best value for K neighbors trying to avoid the Curse of Dimensionality.

![image](https://user-images.githubusercontent.com/86802852/152808843-2dcf2ed2-27ec-4111-9784-75a747fcb8d1.png)


## [Project 2: Wine Quality](https://github.com/andreeamariacovaciu/Wine-Quality)
The purpose of this project is to classify the wine by its quality considering some features like alcohol, sulphates, volatile acidity, total sulfur dioxide and others.
To do that I used the Random Forest Classifier algorithm from scikit-learn library.  
For the model evaluation I used the accuracy score metrics. GridSearchCV helps evaluate all combinations of parameters I defined (n_estimators, max_depth and criterion) to find out the best ones, then I re-fitted the model with the new parameters, so the accuracy score increases.

## [Project 3: Car price prediction](https://github.com/andreeamariacovaciu/Car-price-prediction)

This is a demo project which shows how Machine Learning Models are deployed on production using Flask API

This project has three major parts :
1. model.py - This contains code for the Machine Learning model. to predict cars price based on training data in 'cars.csv' file. The algorithm used is Linear Regression. Taking into consideration that the original dataframe contains 10 features that predict the car price, I chose only the 6 most important features. The other 4 features do not have significant impact on the predicted value.
2. app.py - This contains Flask APIs that receives car details through GUI or API calls, computes the predicted value based on the model and returns it.
3. templates - This folder contains the HTML template to allow user to enter car details and displays the predicted car price.

Enter valid numerical values in all 6 input boxes and hit Predict Car Price.
Then you should  be able to see the predicted car price on the HTML page!

![image](https://user-images.githubusercontent.com/86802852/152191089-fa42546c-3f47-4311-b2bc-68821c80e440.png)

## [Project 4: Final energy consumption in transport by type of fuel in EU](https://github.com/andreeamariacovaciu/EU-Transportation-Fuel)  
Final energy consumption in transport by type of fuel in EU
This is a data analysis project for the Final energy consumption in transport by type of fuel in EU.  
Data source: https://ec.europa.eu/eurostat/web/climate-change/data/database  
Library used for plots: Plotly

## [Project 5: Selenium](https://github.com/andreeamariacovaciu/selenium-project)
The purpose of this project is to collect data from web using Selenium and make predictions based on it.
The data are collected from https://www.bvb.ro/FinancialInstruments/Details/FinancialInstrumentsDetails.aspx?s=m and they represent the price for Medlife stock. Predictions are made using an ARIMA (autoregressive integrated moving average) model. 


## Hope to see you soon because new projects will come!
