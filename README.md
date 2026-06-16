# Movie Recommender System

A Streamlit frontend that calls a FastAPI backend to recommend movies using TMDB and local TF-IDF similarity.

## Live Demo

**[Open Streamlit App](https://heart-disease-prediction-atbjfw7dnxcqwkjqjmia8p.streamlit.app/)**

## 🚀 Features

- Search movies using TMDB
- View movie poster cards and details
- Local TF-IDF recommendations from a precomputed dataset
- Shows TMDB posters, release year, and recommendations
- CORS-ready FastAPI backend for Streamlit frontend

## 📄 API Endpoints

GET /health
GET /home
GET /tmdb/search
GET /movie/id/{tmdb_id}
