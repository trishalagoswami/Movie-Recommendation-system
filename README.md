# Movie Recommendation system
This is a content based filtering movie recommendation project, that predicts which movies are to be recommended to a user based on their previously watched and most rated movies.

# Datasets used
The datasets that havebeen used for the project are the user_ratings.csv dataset, and the movies.csv datasets from MovieLens.

# Brief discussion on the methodology used
This system focuses on finding the correlation between various movies within the dataset. In the beginning, the datasets are wrangled and cleaned to fit the project requirements.

Next, the datsets are merged using pandas library. Then a pivot table is created consisting of the user ratings of each user corresponding to the userIDs. this pivot table is referenced, and a correlation is found for a particular movie with all the other movies, and the movies with the highest correlation are recommended next.
