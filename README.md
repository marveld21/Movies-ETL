# Movies-ETL
## Background
### We were asked to create an automated pipline that takes new data and applys transformations then loads the data into existing tables.

## ETL Function to Read Three Data Files
### I created a ETL_function_test.ipynb file and it is used to create the function that will extract and transform the data into seperate dataframes.

## Extract and Transform the Wikipedia Data
### Leveraging the previous function we have another file (ETL_clean_wiki_movies.ipynb) that will perfrom the extraction and transformation adding filters to clean data.

## Extract and Transform the Kaggle Data
### Perform extract and transform on the Kaggle data then merged it with the Wikipedia data to get movies dataframe and movies with ratings dataframe with the ETL_clean_kaggle_data.ipynb file.

## Create the Movie Database
### After creating all the needed dataframes we load the data into a PostgreSQL database with the ETL_create_database.ipynb file.