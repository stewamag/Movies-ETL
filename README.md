# Movies-ETL

Analysis of movie data for Amazing Prime.

## Purpose:

To extract data from three different sources (wikipedia, kaggle, and a reviews website), transform them by cleaning them and creating data frames in jupyter notebook, and upload them using PostgresSQL into pgAdmin.

## Results:

### Extract:

These were the original data sets from:

Wikipedia:

<img width="1006" alt="wiki_movies_df" src="https://user-images.githubusercontent.com/106691255/187089796-dc6b54cf-cfc7-47a2-a0be-c54d6f09e43a.png">

Kaggle Reviews:

<img width="262" alt="ratings_df" src="https://user-images.githubusercontent.com/106691255/187089792-2351b96f-6fcb-478f-9c60-d854c3845794.png">

Kaggle Movie Metadata:

<img width="1007" alt="kaggle_metadata" src="https://user-images.githubusercontent.com/106691255/187089786-d8919dad-14e8-4432-9665-fde306889991.png">

### Transform: 

Wikipedia:

<img width="993" alt="wiki_movies_df_updated" src="https://user-images.githubusercontent.com/106691255/187089825-f23cba10-1bc7-4b84-94e7-6311cb576909.png">

Kaggle Movies and Ratings:

<img width="996" alt="movies_with_ratings_df" src="https://user-images.githubusercontent.com/106691255/187089833-e3597a52-6e9b-41e9-8063-71fb52844332.png">

### Load:

The code and output to send the table to PostgresSQL:

<img width="814" alt="Send_to_SQL" src="https://user-images.githubusercontent.com/106691255/187089852-3593677b-1aa2-424c-a0b7-4be87fa9d6ab.png">

The output:

<img width="1019" alt="extract_transform_load" src="https://user-images.githubusercontent.com/106691255/187089867-b4a9e43e-2343-4a64-b664-9c12ea5c7b62.png">


## Results:

The data was cleaned and organized into two final tables - movies and ratings. This will allow Amazing Prime to decide which movies are worth purchasing the streaming rights to.
