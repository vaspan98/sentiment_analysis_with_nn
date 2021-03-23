# recurrent_neural_net
Sentiment Analysis on Tweets using Recurrent Neural Networks

## Description / Goals 
Our goal is to develop a sentiment classifier using different bidirectional stacked RNNs with LSTM/GRU cells for a Twitter Sentiment Analysis dataset.
We experiment with different word embeddings (tf-idf, GloVe) and parameters as:
* the number of stacked RNNs
* the number of hidden layers
* the type of cells 
* gradient clipping 
* dropout probability

1. We compare our models based on the loss convergence and the basic score metrics (Precision, Recall, F1-Score).
2. We evaluate our experiments based on the mathematical-theoretical background of each model.  
3. We plot the Loss - Epochs diagrams and the ROC curve of our best model to visualize the outcomes of our experiments.
