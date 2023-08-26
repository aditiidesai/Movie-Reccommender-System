# Movie-Reccommender-System
This project was done as a part of a Machine Learning Course. 

The aim of this project is to build a recommender movie system
It is based on the past preferences of users on movies and their ratings
It will result in a web app with simple UI to portray the above.

Unsupervised Learning Algo: K- nearest neighbours (KNNs)
cosine similarity

Collaborative Filtering is a technique or a method to predict a user’s taste and find the items that a user might prefer on the basis of information collected from various other users having similar tastes or preferences

User based Collaborative Filtering:
INPUT: user id, k similar users, numb of movies to recommend
-knn gives top k users similar in taste to the user id we enter
-return top n movies that are viewed by those users

Item based Collaborative Filtering:
INPUT: movie name, numb of movies req as suggestions
-knn gives top n movies similar to movie entered
