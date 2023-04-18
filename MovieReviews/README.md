## Overview:

This project focuses on natural language processing and sentiment analysis of movie reviews. The primary goal is to develop a machine learning model that accurately predicts whether a review is positive or negative based on the text. The project employs Python programming language and various popular libraries to preprocess the data, train a machine learning model, and evaluate its performance.

## Dependencies:

* Python 3.7+
* Pandas
* Numpy
* Scikit-learn
* NLTK
* Requests

To install the required libraries, run the following command:

$ pip install pandas numpy scikit-learn nltk requests

## Dataset:

The dataset used in this project is the IMDb movie review dataset, which consists of 50,000 movie reviews labeled as either positive or negative. The dataset can be downloaded directly using the provided URL:

* IMDb Movie Review Dataset: http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz

In this script, the download_data() function downloads the IMDb dataset using the provided URL. The load_data() function reads the data and creates a pandas DataFrame. The preprocess_data() function preprocesses the text data. The main() function vectorizes the text data, trains a Naive Bayes classifier, and evaluates the model.