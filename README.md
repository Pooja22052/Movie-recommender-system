# Movie-recommender-system
This repository contains a comprehensive movie recommender system built using state-of-the-art machine learning techniques. The system utilizes a dataset of movies and user preferences to provide personalized movie recommendations to users.





Motto: "Unlock Your Cinematic Journey!"
This movie recommendation system is content based system which is designed to assist users in finding movies that align with their interests and preferences. By leveraging different algorithms and data analysis, the recommendation system provides personalized movie suggestions, saving users the time and effort of searching through extensive movie libraries. The system aims to enhance users' movie-watching experience and enjoy discovering new movies that captivate and entertain you and embark on a cinematic journey like never before.
Dataset link: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
Movie Recommendation: The system takes user input in the form of a movie title and recommends similar movies based on the input. It utilizes a precomputed similarity matrix to calculate the similarity scores between movies and selects the top recommendations.
Movie Details: For each recommended movie, the system fetches additional details such as the movie poster and IMDb ID using the Movie Database (TMDb) API.
Sentiment Analysis: The system scrapes reviews from IMDb for each recommended movie using the IMDb ID. It performs sentiment analysis on the reviews using a pre-trained model to classify them as "Good" or "Bad".

Web Interface: The system provides a web interface implemented using Flask, allowing users to access and interact with the recommendation system through a web browser. It includes the following pages:
Homepage: Provides an overview of the system.
Recommend: Allows users to enter a movie title and receive recommendations.
Reviews: Displays the reviews for a selected movie.
Dataset and Pretrained Models: The system utilizes a dataset (dataset.csv) containing movie information and precomputed models (similarity.pkl, npl_vectorizer.pkl, reviews_model.pkl) for recommendation, vectorization, and sentiment analysis, respectively.
Integration of External APIs: The system integrates with the TMDb API to fetch movie details and uses web scraping techniques to extract reviews from IMDb.

Experimental setup dependencies:
1.	Python: Make sure you have Python installed on your system. 
2.	Flask: The code uses the Flask framework for building the web application. 
3.	NumPy: NumPy is a library for numerical computations in Python. 
4.	Pandas: Pandas is a powerful data manipulation library. It is used for reading and manipulating the movie dataset. 
5.	scikit-learn: scikit-learn is a machine learning library that provides various tools for data pre-processing and modeling. It is used for vectorization and cosine similarity calculations.
6.	BeautifulSoup: BeautifulSoup is a library used for web scraping. It is used to extract movie reviews from IMDb.  
7.	html5lib: html5lib is an HTML parser used by BeautifulSoup. It is required for parsing IMDb reviews. 
8.	Pickle: Pickle is a Python module used for serializing and deserializing Python objects. It is used to load precomputed models and data. 

Users satisfaction is crucial, and feedback through surveys, rating,reviews, user retention rates, and engagement metrices can provide insights into how satisfied users are with the recommendation system
