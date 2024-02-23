# movie-reccomendation-system
Project Summary: Popularity-Based, Content-Based, and Collaborative-Based Movie Recommender System

> Objective Overview:
The project aims to build a movie recommender system with three modules: Popularity-Based, Content-Based, and Collaborative-Based. Users can input a genre (g), minimum ratings threshold (t), and the number of recommendations (N) for each module. The recommendations are based on the popularity within a specified genre, content similarity to a chosen movie, and collaborative filtering using similar users.

> Data Description:

Dataset consists of 105,339 ratings for 10,329 movies by 668 users.
Ratings range from 0.5 to 5, with an average of 3.5.
Two files: Movies.csv (movieId, title, genres) and Ratings.csv (userId, movieId, rating, Timestamp).

> Exploratory Data Analysis (EDA):

Distribution analysis of features, including ratings and genres.
Identification of unique users and movies.
Genre-level analysis, calculating average rating and total movies.
Exploration of unique genres in the dataset.

**Recommendation Modules:**

> Popularity-Based:

Users input a genre (g) and minimum ratings threshold (t).
Recommends top N movies within the specified genre based on popularity, ordered by ratings.
Ensures each recommended movie has at least (t) reviews.

> Content-Based:

Users input a movie (m).
Recommends top N movies based on similar genres to the chosen movie (m).
Utilizes content similarity to suggest relevant movies.

> Collaborative-Based:

Users input a target user (u) and the number of similar users (K).
Recommends top N movies based on the preferences of K similar users to the target user (u).
Collaborative filtering enhances personalization.

>Optional: 

>>GUI Interface:

An optional graphical user interface (GUI) using Python libraries (e.g., ipywidgets) is provided.
Enhances user interaction by allowing them to input parameters and explore recommendations effortlessly.
Conclusion:

The project implements three recommendation modules catering to different user preferences: popularity, content similarity, and collaborative filtering.

EDA provides insights into data distribution, genre-level metrics, and unique users and movies.

The GUI interface offers a user-friendly way to interact with and test the recommendation modules.

This project aims to deliver a comprehensive movie recommender system that covers popular choices, content-based suggestions, and collaborative filtering to enhance user satisfaction and engagement.
