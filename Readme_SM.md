# Movie Recommender 

The goal of this project is to build a movie recommender system using the MovieLens 27 Million dataSet available on Kaggle (https://grouplens.org/datasets/movielens/) 

Implementation steps:

1- The code called "preprocess_SM.ipynb" cleans and shrinks the dataset.

2- The code called "preprocess_dictionary_SM.py" creates the dictionary of topples. The reason behind creating dictionary is to look up values similar to SQL instead of looping through the matrix each time,  which significantly reduces the computational time.

3- The code called "itembased_SM.py" performs the item-item collaborative filtering.

4- The code called "userbased_SM.ipynb" performs the user-user collaborative filtering. 

5- The code called "MF_SM.ipynb" performs matrix factorisation (PCA) to predict the movie rating.
