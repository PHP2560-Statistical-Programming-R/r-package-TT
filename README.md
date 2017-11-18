### Project Contributors

Triet Tran

###Project Goals

The goal of this project is to create a R package called "CrimeDetect" to analyze and predict crime trend in a given data based on past data.

This package will take advantage of the available crime data that has been under-utilized. Crime prevention is essential in the safety of a city and predicting a crime trend would be very much useful.

###Project Breakdown

The project is split into three main sections:

1) Compile crime data through webscrapping 
2) Create a multiple regression model to predict crime trend
3) Use Markov chain to create a simulation model to predict crime trend
4) Compare the results of the two prediction methods

###Steps

1) create_data: this function wil collect data from "https://www.fbi.gov/news/stories/2016-crime-statistics-released"

2) predict_mregression and predict_markov are functions to predict crime trends

3) trend_compare: this function will carry out hypothesis testing of the outcomes by prediction simulation functions

4) we then use the package "testthat" to make sure the package works properly. We will also use mock data for testing