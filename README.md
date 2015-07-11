# Sentiment Analysis with Convolutional Networks

Here is one of my submissions to [Kaggle](http://www.kaggle.com) challenge ['Bag of Words meets Bags of Popcorn'](https://www.kaggle.com/c/word2vec-nlp-tutorial).

It is based on the idea of combining pre-trained word2vec embeddings with convolutional networks proposed by Yoon Kim [http://arxiv.org/abs/1408.5882].

The code consists of two IPython Notebooks:
1. Process Kaggle Dataset Train+Test.ipynb contains data pre-processing.
2. Train CNN IMDB.ipynb implements convolutional network with one convolutional layer.

This model (trained for 3 epochs) yields AUC = 0.96823 (on test data).

Ensemble of three convolutional networks (having different number of convolutional layers and feature maps) gives AUC = 0.97310.

## Dependencies

* Python 2.7
* [IPython 3.0](http://ipython.org/)
* [NumPy](http://www.numpy.org/)
* [Theano 0.7](https://github.com/Theano/Theano/releases/tag/rel-0.7)
* [Keras](https://github.com/fchollet/keras)
* [scikit-learn](http://scikit-learn.org/stable/index.html)
* [Pandas](http://pandas.pydata.org/)
