My Neural-Network-SMS-Text-Classifier Project

This project is a machine learning model that classifies SMS messages as spam or ham using a neural network.

Features
1. Downloads and loads SMS Spam Collection dataset (train and validation TSV files)
2. Builds a machine learning pipeline combining TF-IDF vectorization and Multinomial Naive Bayes classification
3. Transforms text data into weighted numerical features using bigrams (1–2 n-grams) and a 5000-word vocabulary limit
4. Trains a Naive Bayes model with Laplace smoothing (alpha = 0.3) to predict spam or ham messages
5. Evaluates model predictions on sample test messages for real-world message classification
6. Implements a custom test suite comparing predictions to expected labels for automated model validation
7. Achieves accurate binary classification through probabilistic modeling of word frequencies
