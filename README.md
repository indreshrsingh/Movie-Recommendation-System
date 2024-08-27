# Movie Recommendation System

## Overview
This project is a sophisticated movie recommendation system that utilizes the TMDB dataset of over 5000 movies. It combines content-based filtering and collaborative filtering techniques to provide personalized movie recommendations.

## Features
- Content-based movie recommendations using movie descriptions, genres, and keywords
- Item-based collaborative filtering using ratings from 500+ users
- User-friendly interface for interacting with the recommendation system
- CRUD operations for managing movie data

## Technologies Used
- Python
- TMDB API
- Streamlit
- SQLite
- Scikit-learn (for TfidfVectorizer)
- Pandas
- NumPy

## Methodology
1. **Content-Based Filtering**:
   - Text Vectorization using TfidfVectorizer
   - Stemming for text preprocessing
   - Cosine similarity for finding comparable movies

2. **Collaborative Filtering**:
   - Item-based approach
   - Utilizes ratings from a diverse user base

