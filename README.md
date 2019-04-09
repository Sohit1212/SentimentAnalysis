# SentimentAnalysis
This is Sentiment Analyzer for the data obtained from Imdb Movie Reviews. The reviews have been clasified into positive and 
negative and the model has been trained using SVM. The hyperparameter has been chosen carefully by hit and try method.
The model is dumped into model.pkl file using the python library pickle.
This model is then used to create a web application using Flask, where user gives the review and then the model classifies 
whether it is negative or positive.
