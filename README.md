# COMP4332_Project_1
This project is about sentiment analysis on a set of 20000 movie reviews.
Our aims is to convert these review to a rating of 5.
18000 movie reviews are used as training, and the remaining is used for validation.

## First model
### CountVectorizer with Logistics Regression
1. Data is being preprocessed by removing stopword and stemming
2. Data is passed into CountVectorizer to change into a form of (token, frequency)
3. Data is passed into Logistics Regression for training and predictation

## Second model
### LSTM
1. Data is being preprocessed by removing stopword and stemming
2. Data is passed into LSTM
3. It is then output to a ReLu and fully connected layer for predictation

## Third model
### BERT
1. Data is being tokenize
2. Data is then passed into BERT for fine tuning.
3. After 3 epochs, it has higher accuracy than the first second model

## Summary
BERT > Logistics regression > LSTM
Our data is not balance so different effects may happen using different data sets
