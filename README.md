# Intelligent-Programming
This project is a content-based movie recommender system built using the MovieLens 100K dataset. It helps users discover movies that are similar in content and genre to a movie they already like.

📌 Features

🧹 Data Cleaning:

Extract movie titles, genres, and release years from the raw MovieLens data.

Handle missing values and format columns for analysis.

📊 Data Visualization:

Plot movie release trends by year.

Explore the distribution of genres across the dataset.

🧠 Content-Based Filtering:

Create a Bag of Words using movie titles and genre labels.

Vectorize the data using TF-IDF Vectorizer.

Calculate similarity between movies using cosine similarity.

🔍 Recommendation Engine:

Input a movie title and get the top 10 most similar movies.

Title matching supports flexible input (e.g., "Star Wars" will find "Star Wars (1977)").

💾 Model Persistence:

Save the processed movie list and similarity matrix using pickle for later use.
