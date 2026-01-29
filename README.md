Movie Recommendation System
This project implements a movie recommendation system using collaborative filtering on the MovieLens 100K dataset. The system suggests movies similar to a given movie based on user ratings.

Features
Data preprocessing and exploratory data analysis (EDA)

Correlation-based movie recommendations

Visualization of ratings distribution and relationships

Dataset
The project uses the MovieLens 100K dataset, which includes:

100,000 ratings from 943 users on 1682 movies

Movie titles and user-item-rating data

Dependencies
Python 3.x

pandas

numpy

matplotlib

seaborn

Files
ml-100k/: Contains the MovieLens dataset

Jupyter notebook with the implementation code

How It Works
Load and preprocess the dataset

Perform exploratory data analysis on ratings

Create a user-item rating matrix

Calculate movie correlations based on user ratings

Generate recommendations for a given movie

Results
The system successfully identifies movies with high correlation to the input movie, filtering by movies with sufficient ratings to ensure recommendation quality.
