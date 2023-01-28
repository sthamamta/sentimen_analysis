# Sentiment Analysis on IMDB dataset using LSTM Network
## Introduction
This project contains Jupyter Notebook with the code for performing sentiment analysis on the IMDB dataset using a Long Short-Term Memory (LSTM) network. The dataset consists of 25,000 movies reviews from IMDB, labeled by sentiment (positive/negative). The goal of this project is to train an LSTM network to classify the reviews based on their sentiment.

## Requirements
Python 3.6 or higher
Jupyter Notebook
TensorFlow 2.x
Keras
Numpy
Matplotlib

### Data Preparation
The dataset is already provided in the notebook and preprocessed to be ready for use. The dataset is splitted into training and testing sets.

### Model Training
The notebook contains the code for building the LSTM model using Keras. The model consists of an Embedding layer, LSTM layer and a dense layer. After building the model, it is then trained using the training set with a batch size of 64 and 30 epochs.

### Model Evaluation
After training, the model is evaluated using the testing set and the accuracy and loss are calculated and plotted in a graph for better visualization.





