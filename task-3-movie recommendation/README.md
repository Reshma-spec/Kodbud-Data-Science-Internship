# Movie Recommendation System

## Overview

This project implements a Content-Based Movie Recommendation System using the MovieLens dataset. The system recommends movies based on genre similarity by applying Natural Language Processing (NLP) techniques and Cosine Similarity.

## Objectives

* Build a simple recommendation system using movie genres.
* Learn the fundamentals of content-based filtering.
* Use Cosine Similarity to find similar movies.
* Visualize genre distribution within the dataset.

## Dataset

The project uses the MovieLens Small Dataset, which contains:

* Movies information (title and genres)
* User ratings
* Tags and links

Dataset Source:
https://grouplens.org/datasets/movielens/

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Methodology

### 1. Data Collection

Loaded the MovieLens dataset and selected relevant movie information.

### 2. Data Preprocessing

* Removed unnecessary columns.
* Processed movie genres.
* Converted genre text into numerical features using CountVectorizer.

### 3. Similarity Calculation

Applied Cosine Similarity to measure the similarity between movies based on genres.

### 4. Recommendation Engine

Created a function that:

* Accepts a movie title as input.
* Finds similar movies using similarity scores.
* Returns the top recommended movies.

## Visualization

A bar chart was created to display the most common movie genres in the dataset.

## Results

The recommendation system successfully suggests movies with similar genres to the selected movie. This demonstrates the basic working of content-based recommendation systems used in real-world applications.

## Project Structure

```
Movie-Recommendation-System/
│
├── movies.csv
├── ratings.csv
├── links.csv
├── tags.csv
├── Movie_Recommendation_System.ipynb
└── README.md
```

## Sample Recommendation

Input:

```
Toy Story (1995)
```

Output:

```
Toy Story 2 (1999)
A Bug's Life (1998)
Monsters, Inc. (2001)
Finding Nemo (2003)
Cars (2006)
```

## Future Improvements

* Add collaborative filtering.
* Use movie descriptions and tags.
* Build a web application using Streamlit.
* Improve recommendation accuracy with hybrid models.

## Conclusion

This project demonstrates how content-based filtering and cosine similarity can be used to build a simple yet effective movie recommendation system. It serves as an introduction to recommendation systems and machine learning concepts.
