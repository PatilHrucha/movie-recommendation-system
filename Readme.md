# Movie Recommendation System

## Project Overview

The Movie Recommendation System is a Machine Learning project that recommends movies similar to the movie selected by the user. This project uses a **Content-Based Recommendation System**, where movies are recommended based on their content such as genres, keywords, cast, crew, and overview.

The recommendation system calculates the similarity between movies using **Natural Language Processing (NLP)** and **Cosine Similarity**.



##  Objectives

- Build a movie recommendation system using Machine Learning.
- Recommend similar movies based on movie content.
- Learn data preprocessing and feature engineering.
- Understand the use of NLP techniques in recommendation systems.



##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- NLTK

---

## Dataset

The project uses the **TMDB 5000 Movie Dataset**.

Files used:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

The dataset contains information such as:

- Movie Title
- Overview
- Genres
- Keywords
- Cast
- Crew


##  Machine Learning Concepts Used

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Natural Language Processing (NLP)
- Stemming
- CountVectorizer
- Cosine Similarity
- Content-Based Filtering



##  Project Workflow

1. Import the required libraries.
2. Load the movie and credits datasets.
3. Merge both datasets.
4. Select the required columns.
5. Remove missing values.
6. Extract genres, keywords, cast, and director.
7. Create a combined **tags** column.
8. Convert text into numerical vectors using CountVectorizer.
9. Calculate Cosine Similarity.
10. Recommend the top 5 similar movies.

---

##  Sample Output

### Input

```python
recommend("Avatar")
```

### Output

```
Movies Recommended for Avatar:

Aliens vs Predator: Requiem
Aliens
Falcon Rising
Independence Day
Titan A.E.
```


##  Project Structure

```
Movie Recommendation System/
│
├── movie_recommendation.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── movies.pkl
├── similarity.pkl
├── README.md
```



##  How to Run the Project

1. Download the project files.
2. Open the project in Jupyter Notebook.
3. Install the required libraries.

```bash
pip install pandas numpy scikit-learn nltk
```

4. Run all notebook cells in sequence.
5. Call the recommendation function.

Example:

```python
recommend("Avatar")
```

---

##  Future Enhancements

- Develop a web application using Streamlit.
- Add movie posters using the TMDB API.
- Improve recommendations using Collaborative Filtering.
- Allow users to search movies through a graphical interface.

---

##  Conclusion

This project demonstrates how Machine Learning and Natural Language Processing can be used to build a Content-Based Movie Recommendation System. By analyzing movie features and calculating similarity scores, the system successfully recommends movies that are closely related to the user's selected movie.

---

##  Author

**Name:** Hrucha Patil

**Internship:** AIML Internship

**Project:** Movie Recommendation System
