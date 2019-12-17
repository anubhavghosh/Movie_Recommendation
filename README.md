# Movie_Recommendation
The weekend movie trip


Here is a glimpse of what I have done. For more understanding, please check the jupyter notebook
Recommender Systems with Python
In this notebook, I will be developing a basic recommendation system by suggesting items that are most similar to a particular item, in this case, movies. Keep in mind, this is not a true robust recommendation system, to describe it more accurately,it just tells you what movies/items are most similar to your movie choice.

# Recommending Similar Movies
In the next step, I am going to create a matrix that has the user ids on one access and the movie title on another axis. Each cell will then consist of the rating which the user gave to that movie. There will be a lot of NaN values, because most people have not seen most of the. movies.

Let's choose Braveheart.
Correlation	num of ratings
title		
Braveheart (1995)	1.000000	245
Batman Begins (2005)	0.610550	116
Ocean's Eleven (2001)	0.575751	119
Inception (2010)	0.555414	165
Matrix, The (1999)	0.496045	280

