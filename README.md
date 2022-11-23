# Spam Classifier
<h6>Forking and cloning is welcome. Push changes to get access.<h6>
<br>

A neural network to filter out valid/legit messages from incoming spams. 
Might work on deployment soon...

Stuff used:
SpamSMS dataset from kaggle
Data cleaning and preprocessing with 're' and 'NLTK'
  1. Lemmatization since I think it should work better thank Porter Stemming.
  2. Bag of Words to convert to vectors as TF-IFD made all the values exteremly small, leading to majority of words being labelled 0 when they should be 1.
  <h6> might try fixing it and use TF-IFD only
An ANN with educated guesses for the most part. 
