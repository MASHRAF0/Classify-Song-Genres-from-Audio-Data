# Classify Song Genres from Audio Data
## Description

Over the past few years, streaming services with huge catalogs have become the primary means through which most people listen to their favorite music. But at the same time, the sheer amount of music on offer can mean users might be a bit overwhelmed when trying to look for newer music that suits their tastes.

For this reason, streaming services have looked into means of categorizing music to allow for personalized recommendations. One method involves direct analysis of the raw audio information in a given song, scoring the raw data on a variety of metrics. Today, we'll be examining data compiled by a research group known as The Echo Nest. Our goal is to look through this dataset and classify songs as being either 'Hip-Hop' or 'Rock' - all without listening to a single one ourselves. In doing so, we will learn how to clean our data, do some exploratory data visualization, and use feature reduction towards the goal of feeding our data through some simple machine learning algorithms, such as decision trees and logistic regression.

![CRobot Playing Music](https://solvanam.com/wp-content/uploads/2019/11/computer-band.jpg)

## Libraries & Packages

![numpy](https://img.shields.io/badge/Numpy-%25100-blue)
![pandas](https://img.shields.io/badge/Pandas-%25100-brightgreen)
![Matplotlib](https://img.shields.io/badge/Matplotlib-100-informational)
![ScikitLearn](https://img.shields.io/badge/ScikitLearn-%25100-red)

## Dataset

🏆 To begin with, let's load the metadata about our tracks alongside the track metrics compiled by The Echo Nest. A song is about more than its title, artist, and number of listens. We have another dataset that has musical features of each track such as danceability and acousticness on a scale from -1 to 1. These exist in two different files, which are in different formats - CSV and JSON. While CSV is a popular file format for denoting tabular data, JSON is another common file format in which databases often return the results of a given query.


## Project Steps 

* First, we will start off by loading and viewing the dataset.
* We will see that the dataset has a mixture of both numerical and non-numerical features, that it contains values from different ranges, plus that it contains a number of missing entries.
* We will have to preprocess the dataset to ensure the machine learning model we choose can make good predictions.
* After our data is in good shape, we will do some exploratory data analysis to build our intuitions.
* Finally, we will build a machine learning model that can predict if an individual's application for a credit card will be accepted.



