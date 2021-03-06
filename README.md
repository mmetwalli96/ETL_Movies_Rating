# Project Overview

Prepare a dataset for a hackathon about predicting movies that will gain popularity onces it is hosted on a streaming service. Data will be gathered from Wikipedia and Kaggle, then they will be combined and saved on PostgreSQL database so that the hackathon participants have a nice, clean dataset to use.

# Project Tasks

-  Write a function that reads in the three data files and creates three separate DataFrames.
-  Extract and transform the Wikipedia data to merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.
- Extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.
- Add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
