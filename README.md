# Extract, Transfrom, Load Movie Data 
Module 8 ETL - Extract, Transform, Load Movie Data

## Overview
The purpose of this project was to gather movie data from two different sources, and then perform data cleaning/ transformation and finally load into the database for further analysis.

In order to do these, I extracted the neccessary data from Wikipedia and Kaggle, used python's pandas sqlalchamy and psycopg2 libraries to transform the data into a working dataframe, and then loaded it to movies_data Database using PostgreSQL.

### Assumptions
* Password is defined in config.py file.
* While appending or inserting data into table assuming data has same column names and also same type.
* Requirs pandas, sqlalchamy, psycopg2 python libraries.


## Results

After completing the extract, transform, and load process, I had a database with two tables: one for movies and one for ratings. 

The movies table consists of 31 columns holding a range of information for 6048 different movies.

![Movies_Query](/resources/movies_query.png)

 The ratings table consists of 5 different columns holding a range of information on over 26 million individual user ratings.

![Rating_Query](/resources/ratings_query.png)

 Together, students will have a chance to preform various different analysis from these tables to derive all sorts of interesting insights.
