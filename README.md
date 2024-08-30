# Hybrid Movie Recommendation System

# Overview

This project implements a hybrid recommendation system that combines both collaborative filtering (using matrix factorization like SVD) and content-based filtering (using TF-IDF and cosine similarity). The system is designed to provide personalized movie recommendations by leveraging the strengths of both recommendation techniques.

# Features

- Collaborative Filtering: Uses Singular Value Decomposition (SVD) to factorize a user-item interaction matrix and provide recommendations based on user preferences.
- Content-Based Filtering: Utilizes TF-IDF vectorization and cosine similarity to recommend movies with similar content (e.g., genre, description).
- Hybrid Approach: Integrates the results from both collaborative and content-based filtering to generate a final set of recommendations.

# Dataset
The dataset used in this project is the Netflix dataset, which includes metadata for movies and TV shows.
