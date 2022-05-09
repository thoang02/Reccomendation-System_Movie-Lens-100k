# Reccomendation-System_Movie-Lens-100k

Content-based and Collaborative Filtering for Recommendation System

Dataset: https://grouplens.org/datasets/movielens/100k/
Important files:
-  u.data: Includes ratings of 943 users for 1682 movies. Each user rates at least 20 movies. Rating timestamp is ignored while buidling these models
-  ua.base, ua.test, ub.base, ub.test: 2 ways to split the dataset into training and test sets. These models are built on ua.base and ua.test
-  u.user: Users data, including id, age, gender, occupation, zipcode. Only 'user id' is used to build these models. 
-  u.genre: 19 movie genres, including: unknown, Action, Adventure, Animation, Children's, Comedy, Crime, Documentary, Drama, Fantasy, Film-Noir, Horror, Musical, Mystery, Romance, Sci-Fi, Thriller, War, Western.
-  u.item: information of each movie, including id, name, date, imdb link, and a string of binary 0,1 to indicate which of 19 genres is this movie. A movie can be categorized in many genres. 
This information is used to build item profiles. 


