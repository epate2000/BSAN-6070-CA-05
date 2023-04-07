**BSAN 6070 CA-05**

The link to the dataset can be found here: https://github.com/ArinB/MSBA-CA-
Data/raw/main/CA05/movies_recommendation_data.csv

In this assignment, our goal is to build a k-Nearest Number algorithm in order to create a movie-recommending program. 
We are given a data set containing numerous different movies, and need to find the 5 most similar movies based on what the k-Nearest Number algorithm tells us.

Before creating the algorithm, preliminary steps should be taken such as data cleaning. Checking for any duplicates and null values should be done before moving forward.

Knowing this, we consider the following as per the assignment: Imagine a user is navigating your recommendation website, and he/she encounters a movie named “The Post”. The user is not sure if he/she wants to watch it, but its genres intrigue the user; he/she is curious about other similar movies. The user scrolls down to the “More Like This” section to see what recommendations your recommendation website will make, and the back-end algorithmic gears begin to turn. Your website sends a request to its back-end for the 5 movies that are most similar to The Post. The back�end has a recommendation data set exactly like ours. It begins by creating the row representation (better known as a feature vector) for The Post, then it runs a program similar to the one below to search for the 5 movies that are most similar to The Post, and finally sends the results back to the user at your website.

“The Post” contains the following stats: IMDB Rating = 7.2, Biography = Yes, Drama = Yes, Thriller = No, Comedy = No, Crime = No, Mystery = No, History = Yes

