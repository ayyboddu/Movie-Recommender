# Movie Recommender
A Movie Recommendation System using BERT and Cosine Similarity

## Overview

Welcome to our Movie Recommendation System! This project aims to provide users with movie recommendations based on their input preferences, effectively reducing the time spent searching for suitable movies to watch across various streaming platforms. Our recommendation system utilizes the BERT (Bidirectional Encoder Representations from Transformers) model and content-based filtering approach to analyze movie synopses and provide relevant suggestions.

## Problem Statement

In today's era of numerous streaming services, users often face the challenge of mindlessly scrolling through various platforms to find a movie to watch. On average, people spend approximately 23 minutes a day searching for a movie, which accumulates to a staggering 1.3 years in their lifetime. Our objective is to tackle this problem by using machine learning to offer personalized movie recommendations to users, minimizing the time wasted in searching.

## Performance Criteria

Our Movie Recommendation System aims to achieve the following performance criteria:

1. Provide users with 3 movie recommendations based on their input movie.
2. Give predictions based on user input, ensuring accurate and relevant results.
3. Offer recommendations from across all streaming platforms, eliminating platform limitations.
4. Utilize content-based filtering to analyze movie titles, overviews, genres, cast, directors, etc.
   
## Methodology

Our Movie Recommendation System is built on the following methodology:

1. Use the BERT model to convert movie synopses into a vector space for analysis.
2. Employ cosine similarity to compare movies based on their synopses and identify the most similar ones.
3. Filter and rank the movies to provide the user with the top 3 recommendations.

## Dataset

We utilize the "The Movies Dataset" from Kaggle, containing data from 45,000 movies released on or before July 2017, including cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, and countries. After pre-processing, we have approximately 10,000 movies left for analysis.

## Validation and Results

Our recommendation system has been validated by testing it with various movie inputs of different genres, age ratings, and themes. The system accurately provided relevant recommendations with high similarity scores based on movie overviews.

## Limitations

While our model is effective, it does have some limitations, such as limited consideration for movies released after July 2017, case-sensitivity for movie titles, and computational expense.

## Future Work

In the future, we plan to enhance the user interface, add filtering options, track watch history, specify streaming platforms for recommendations, and implement a user feedback system to improve future recommendations.

We hope you enjoy using our Movie Recommendation System and find it helpful in discovering your next favorite movie!
