# Assignment2_Dave3625
Assignment 2, Dave3625, Introduksjon til kunstig intelligens

We picked the first use case. We want to predict the stock market price for Norwegian airlines.

Regression is the best algorithm for this use case beacause we want to predict a continous quantity.
We want the algorithm to return a stock price based on a historic price data model.
Classification could also work if we wanted to predict whether the price would go up or down, but for this scenario
regression is the best option.


According to several websites Random Forest Regression is not made for predicting beyond the range in the training data. We spent a long time 
trying to find a way to to this because of the way we interpreted the assignment. The way we ended up solving it was by using the loc-method with a date
that exists in the test-dataset. One of the limits of this is that searching on dates that were not in the y_test will not return a price. 
We also showed the results using graphs.
