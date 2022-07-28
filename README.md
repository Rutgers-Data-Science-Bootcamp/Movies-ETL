# Movies-ETL
### Extract, Load, and Transform (ELT) 
## Background 
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Amazing Prime needs to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 

## Main aim of the project
Create an automated pipeline for Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## The workflow 
     1: Write an ETL Function to Read Three Data Files
          Using or knowledge of Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.
     2: Extract and Transform the Wikipedia Data
          Using our knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates
     3: Extract and Transform the Kaggle data
          Using our knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.
     4: Create the Movie Database
         Use our knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
         
## Summary
We extracted really messy and almost unusable data, combed through it carefully to transform it, and then loaded it into a SQL database. Now the data analysing team has a reliable, clean dataset just begging to be analyzed.

### Programming language and Softwares  
Python, SQL, PgAdmin, Postgres

### Data resoureces
wiki_movie_data, kaggle_metadata, ratings
