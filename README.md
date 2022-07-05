# Movie-genres-prediction
NLP project done as a final assignment during the Deep Learning for NLP course @ UW in summer semester of academic year 2021/22. 

## Overview
The aim of the project was to create a model that would fairly well predict movie genre'a tags given plot summary of a movie. 

## Dataset
The dataset used for training DL model is a part of IMDB database of movies and particularly comes from 
this website: https://www.kaggle.com/datasets/cryptexcode/mpst-movie-plot-synopses-with-tags.

### Data preprocessing 
Whilst the dataset is quite large and thus sufficient for training DL models in it's raw it would deliver 
optimal results. As part of cleaning data I've removed duplicate tags as well as stopwords in movie descriptions. 


## Model
The final model is a LSTM based neural network, which architecture can be found in the jupyter notebook. 
However, during the development of this project I played with sever other architectures, among them 
CNN, pure Dense ect.. 





