# Movie Recommendation System

This project implements a movie recommendation system using collaborative filtering and matrix factorization techniques. The system predicts user preferences based on past movie ratings and suggests movies that users are likely to enjoy.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Results](#results)

## Overview
The Movie Recommendation System is built to provide personalized movie recommendations based on users' previous ratings. Using collaborative filtering methods, this system suggests movies that similar users have enjoyed.

## Features
- **Collaborative Filtering**: Provides recommendations by analyzing patterns in user ratings.
- **Matrix Factorization**: Decomposes the user-movie interaction matrix to predict unknown ratings.
- **User-Friendly Interface**: Allows users to input preferences and get movie recommendations.
- **Scalability**: Handles a large dataset of users and movies efficiently.

## Technologies Used
- **Python**: Core programming language used for developing the recommendation system.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-Learn**: Used for implementing collaborative filtering and matrix factorization algorithms.
- **Streamlit**: For creating a simple and interactive interface (optional).
- **Jupyter Notebook**: For developing and testing the code.

## Dataset
The dataset used for this project comes from the **[MovieLens dataset](https://grouplens.org/datasets/movielens/)**, which includes movie ratings from a diverse user base. You can download the dataset [here](https://grouplens.org/datasets/movielens/).

## Results
The model has been evaluated using metrics such as **RMSE** and **Precision at K**. It effectively recommends movies by learning user preferences, achieving satisfactory prediction accuracy.

