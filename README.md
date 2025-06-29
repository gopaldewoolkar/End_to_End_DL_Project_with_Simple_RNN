# End_to_End_DL_Project_with_Simple_RNN

## Simple RNN for IMDB Sentiment Analysis

This repository contains a Python script that builds and trains a simple Recurrent Neural Network (RNN) using Keras and TensorFlow to perform sentiment analysis on the IMDB movie review dataset. The model classifies movie reviews as either positive or negative.

## Overview:
- The project demonstrates a basic workflow for text classification using a Simple RNN. It covers:

- Loading and preparing the IMDB movie review dataset.

- Building a Sequential Keras model with an Embedding layer, SimpleRNN layer, and a Dense output layer.

- Compiling and training the model with EarlyStopping for better training control.

- Saving the trained model.

- Loading the saved model and using it to predict the sentiment of new, unseen movie reviews.

## Dependencies
- Python 3.x
  
- numpy
  
- tensorflow (which includes Keras)

These are automatically installed via pip install numpy tensorflow.
