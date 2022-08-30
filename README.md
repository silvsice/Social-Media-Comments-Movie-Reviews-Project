# Social-Media-Comments-Movie-Reviews-Project

This project contains two main components:

(1) Analyzing social media comments using and metrics extracted from social media sites such as (a) YouTube comments related to movie trailers, (b) YouTube video details of associated trailer, (c) Celebrity Posts/Follower/Following counts from Twitter and Instagram that are related to the movies being analyzed.

(2) Analyzing movie data from various movie databases

These two components are then combined. Whereby the main insight from (1) is sentiment analysis (e.g. polarity, subjectivity), and social media impressions (e.g. view count, like count, popularity), while (2) provides historical movie data such as rating scores, genre, and whether it has won or been nominated for awards.

A series of classification models are then used to predict imdb_rating categories (viable or not viable to invest in). Algorithms used include (a) Random Forest, (b) AdaBoost, (c) Gradiant Boosting, (d) XGBoost, and (e) SVM. Hyperparameter tuning versions and non-hyperparameter tuning versions were used. 

Hypermeter tuning SWM provided the best results (F1 score of 78.30%), but was failed in the validation test. Non-hyperparameter tuning Random Forest provided the second best results (F1 score of 76.79%) and passed the validation test.
