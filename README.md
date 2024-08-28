# Classification-of-Movie-Reviews
Sentiment analysis using a neural network.
Steps:

Load IMDB dataset: Loads the IMDB movie review dataset from Keras, limiting the vocabulary to the top 20,000 most frequent words.
Preprocess data: Creates a vocabulary mapping words to integers, encodes reviews as sequences of integers, and pads sequences to a fixed length.
Build the model: Defines a sequential neural network model with an embedding layer, a flattening layer, a dropout layer for regularization, a dense layer, and a final dense layer with sigmoid activation for binary classification.
Compile and train the model: Compiles the model using the Adam optimizer and binary cross-entropy loss, and trains it on the training data for 5 epochs.
Visualize accuracy: Plots the training and validation accuracy over epochs.
Extract embeddings: Defines a function to extract the output of the embedding layer.
Visualize embeddings: Plots the embeddings of words in a 2D scatter plot.
Plot review embeddings: Defines a function to plot the embeddings of words in a review, highlighting words that are far from the origin.
