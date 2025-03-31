# Personalized Movie Recommendation System

## Overview
This project builds a personalized movie recommendation system using the MovieLens dataset, mimicking Netflix’s recommendation engine. It demonstrates skills in data science, machine learning, and user-focused design, relevant to companies like Netflix. The system uses Singular Value Decomposition (SVD) from the `scikit-surprise` library to predict user ratings and recommend movies.

### Key Features
- **Exploratory Data Analysis (EDA)**: Visualizations of rating distributions and most-rated movies.
- **Model Training**: Hyperparameter tuning of the SVD model using GridSearchCV.
- **Evaluation**: Comparison of actual vs. predicted ratings with a scatter plot.
- **Recommendations**: Top 5 movie recommendations for a user, including genres.

## Dataset
- **Source**: MovieLens 100K dataset (small version) from GroupLens.
- **Details**: 100,836 ratings from 610 users on 9,724 movies, with ratings from 0.5 to 5.
- **Files**:
  - `ratings.csv`: User ratings (userId, movieId, rating, timestamp).
  - `movies.csv`: Movie details (movieId, title, genres).

The dataset files are included in this repository for convenience.

## Setup Instructions
To run this project, you’ll need to use Google Colab (or a local environment with the required libraries installed).
