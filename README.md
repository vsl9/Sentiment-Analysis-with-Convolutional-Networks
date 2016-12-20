# Sentiment Analysis with Convolutional Networks

Here is one of my submissions to [Kaggle](http://www.kaggle.com) challenge ['Bag of Words meets Bags of Popcorn'](https://www.kaggle.com/c/word2vec-nlp-tutorial).

It is based on the idea of combining pre-trained word2vec embeddings with convolutional networks proposed by Yoon Kim [http://arxiv.org/abs/1408.5882].

The code consists of two IPython Notebooks:

1. Process Kaggle Dataset Train+Test.ipynb contains data pre-processing.

2. Train CNN IMDB.ipynb implements convolutional network with one convolutional layer.

This model (trained for 3 epochs) yields AUC = 0.96823 (on test data).

Ensemble of three convolutional networks (having different number of convolutional layers and feature maps) gives AUC = 0.97310.

## Dependencies

* Python 2.7.11
* [IPython / Jupyter Notebook](http://ipython.org/)
* [NumPy](http://www.numpy.org/)
* [Theano 0.8.2](https://github.com/Theano/Theano/releases/tag/rel-0.8.2)
* [Keras 1.2.0](https://github.com/fchollet/keras/releases/tag/1.2.0)
* [scikit-learn 0.17.1](https://github.com/scikit-learn/scikit-learn/releases/tag/0.17.1)
* [Pandas](http://pandas.pydata.org/)
