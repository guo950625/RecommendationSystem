# Recommendation System
## Contents
Generally, there are three categories of recommendation systems: content based systems, collaborative filtering systems, and hybrid systems. And we are going to work on the first two algorithms in this lab.

The collaborative filtering systems is based on: when two users share the same taste on one movie, they might have same taste on another. For example: when user A and B both love movie 1, and A love movie 2, then B might also love movie2.

The content-based filtering systems is based on: the similar movie. That's to say, if movie 1 and 2 is similar, after reading movie 1, the user might also love movie 2


<center>
<img src="image/two_approach.png" width=600 />
</center>

KNN will be used in this project for recommendation.

KNN is a machine learning algorithm to find clusters of similar movies based on common movie ratings, and make predictions using the average rating of top-k nearest neighbors

KNN will calculate the “distance” between the target movie and every other movie in its database, then it ranks its distances and returns the top K nearest neighbor movies as the most similar movie recommendations.

## How to run
Simply, git clone the whole repository and then just start your trip in Recommendation System!!
