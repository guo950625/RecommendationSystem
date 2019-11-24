# Recommendation System
## Contents
Generally, there are three categories of recommendation systems: content based systems, collaborative filtering systems, and hybrid systems.

The collaborative filtering systems is based on: when two users share the same taste on one movie, they might have same taste on another. For example: when user A and B both love movie 1, and A love movie 2, then B might also love movie2.

The content-based filtering systems is based on: the similar movie. That's to say, if movie 1 and 2 is similar, after reading movie 1, the user might also love movie 2

The hybrid systems, as name indicated, is the combination of the other two

<center>
<img src="image/two_approach.png" width=600 />
</center>

Theoratically speaking, these are the generally used recommendation algorithms, in which, KNN will be used in this project

KNN is a machine learning algorithm to find clusters of similar movies based on common movie ratings, and make predictions using the average rating of top-k nearest neighbors

KNN will calculate the “distance” between the target movie and every other movie in its database, then it ranks its distances and returns the top K nearest neighbor movies as the most similar movie recommendations.

## How to run
Simply, git clone the whole repository and then just start your trip in Recommendation System!!
