# Poster Genre Classification Using CNN
We used following datasets for the project.
- CSV file link : https://www.kaggle.com/grouplens/movielens-20m-dataset
   This is the link for the CSV file which contains title of the movies and their corresponding genres. There were total 27278 movies in the file. Each movie is classified in a few    of the 20 genres. Of the 20 genres one was "No genre available".
- Movie Poster Dataset  : https://www.kaggle.com/ghrzarea/movielens-20m-posters-for-machine-learning
   This is the link for the poster dataset of 26938 of 27278 movies in the above CSV file. We removed the data corresponding to remaining 340 movies (whose posters were not            available) from the CSV file also.
- Final Result - The model gave around 18% accuracy for all genres correct prediction. Here are the top 5 movies on the basis of their recall score.

   | **Genre**    | **Recall** |
   | -------- | ------ |
   | Comedy   | 0.61   |
   | Drama    | 0.53   |
   | Thriller | 0.18   |
   | Horror   | 0.14   |
   | Sci-Fi   | 0.11   |
