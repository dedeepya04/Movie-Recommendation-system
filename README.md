
This is a project on Movie recommendation system that recommends 5 movies to users based on the input movie.
Download datasets tmdb_5000_movies.csv and tmdb_5000_credits.csv from this link:  https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

1) The first step in this process id Data cleaning. It is retaining on useful data such as cast, crew etc.. , removing unwanted data  such as budget,location etc.. and modifying data as we need.
2) We created tags to each movie and coverted  them to vectors. Then we find cosine similarity which  is used to measure the similarity between vectors. It calculates the cosine of the angle between two non-zero
   vectors in a multi-dimensional space, with values ranging from -1 to 1. And the 5 movies that are nearest to the input movie in terms of consine similarity are recommended to users.

   Thus we recommend movies using cosine similarity as helps identify how similar movies are to each other based on their feature representations.
