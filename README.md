Movie Recommendation System

Project Overview

This project is a web-based Movie Recommendation System that recommends movies based on user input. It pulls movie data from the TMDb API and utilizes machine learning techniques to suggest similar films. The system also provides rich details about movies, including cast information and user reviews. The project is built using Flask for the backend and includes a clean, responsive user interface.

Demo

https://movie-recommendationsystem-ad9e205393d5.herokuapp.com

Features

	•	Movie Search: Allows users to search for movies by title and retrieve detailed information (overview, rating, release date, cast, etc.).
	•	Movie Recommendations: Suggests similar movies based on the user’s search.
	•	Cast Information: Displays key details about the cast members.
	•	User Reviews: Provides user reviews and sentiment analysis based on ratings.
	•	Real-Time Data: Leverages the TMDb API to provide the latest information and movie details.
	•	Data Processing: Extensive data cleaning and preparation steps ensure accurate recommendations.
	•	Responsive Design: Works across devices, including desktop and mobile.

 
 Deployment

Steps to Deploy the App:

	1.	Data Extraction: Gather data from IMDb, TMDb, and other movie datasets.
	2.	Exploratory Data Analysis (EDA): Analyze the dataset for patterns and missing data.
	3.	Feature Engineering: Create relevant features for the recommendation system, such as genre frequency or actor collaboration.
	4.	Model Building and Tuning: Build the recommendation engine using cosine similarity and fine-tune the model.
	5.	Building Flask API: Create a RESTful API using Flask to serve the recommendation system.
	6.	Pushing Code to GitHub: Push the complete code to GitHub for version control.
	7.	Connecting to Heroku: Set up a Heroku account and link the GitHub repository.
	8.	Deploy the App: Deploy the app on Heroku to make it accessible online.

 This project was made possible by:

	•	TMDb API for movie data.
	•	Various open-source libraries and frameworks, including Flask, Pandas, and Scikit-learn.
