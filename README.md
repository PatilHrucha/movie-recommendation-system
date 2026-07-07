# Movie Recommendation System

## Project Overview

This project recommends similar movies using a Machine Learning based Content-Based Recommendation System.

## Objective

To recommend movies based on their genres, keywords, cast, crew, and overview using cosine similarity.

## Features

- Content-Based Movie Recommendation
- Cosine Similarity Algorithm
- Interactive Streamlit Web Application
- Fast Movie Search
- Top 5 Similar Movie Recommendations

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- NLTK

## Dataset

TMDB 5000 Movie Dataset

## Algorithm

- Content-Based Filtering
- CountVectorizer
- Cosine Similarity

## Project Structure


movie-recommendation-system/
│── app.py
│── model.py
│── requirements.txt
│── README.md
│── Movie Recommendation System.ipynb
│── movies.pkl


## Installation

```bash
pip install -r requirements.txt
```

## How to Run

First generate the required pickle files:

```bash
python model.py
```

Then start the Streamlit application:

```bash
streamlit run app.py
```

## Output

The application recommends the top 5 most similar movies based on the selected movie.

## Future Improvements

- Movie Posters using TMDB API
- Movie Ratings
- Release Year
- Movie Overview
- Genre Filters
