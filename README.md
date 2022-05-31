# KNN-Classification
Manual classification of seeds data using K-Nearest Neighbor Algorithm without using ML library

This project was used as one of my submission on course final project in my university. It was supposedly to create machine learning code without using any Python library.

The dataset that used in this project is obtained from UCI public dataset. Dataset link: https://archive.ics.uci.edu/ml/machine-learning-databases/00236/seeds_dataset.txt

The code starts by importing the data into a variable. Since the each data is separeted by tab and new line, we can easily convert it into 2-dimension list. Since there is inconsistency in data's tabular, we need to remove missing value first and followed it by converting the remaining data into float type.

For future functionality purpose, we can define some methods first so we can easily called it later. There are 3 methods declared, euclidean method, getKNearest method, and voting method. Euclidean method, stand by it's name, is used to calculate the total data distaance using Euclidian algorithm. getKNearest method is used to get the k lowest value in a list of data. Voting method is used to reduce the bias if some certain class have very larger result than the other class, it's also used to get the final result from all of the k nearest data.

The main part of the code is only contain calling every method that used on a new data. In the end, we can predict if the new data is belong to which class.
