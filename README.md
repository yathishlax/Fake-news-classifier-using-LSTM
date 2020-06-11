Fake-News-Classifier
Goal:
This project is basically focused on identifying the fake news using NLP and LSTM
It is applied using word embedding method

Source:
The source of this dataset is from Kaggle.com
https://www.kaggle.com/c/fake-news/data#

About the dataset:
Dataset contains articles containing the fake news and so machine learning algorithms are used to classify them.
It is split into train and test data for building the model.

Environment
Tensorflow: TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.
Version: '2.2.0', since tf version greater than 2.0 is required since keras is integrated within the tf library.

Features:
id: unique id for a news article
title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
label: a label that marks the article as potentially unreliable
1: unreliable
0: reliable


Approach

•	Text Cleaning
•	One hot representation
•	Word embedding
•	Creating a sequential model
•	Train test split
•	Model Training
•	Model Predicting
•	Hyperparameter by adding drop out layer
•	Calculating accuracy 
