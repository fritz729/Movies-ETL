
# Movies-ETL

## Purpose and Overview

### In this repository, three exhaustive movie datasets from Wikipedia and Kaggle (GroupLens research group) were sourced, and then extracted using Jupyter Notebook with functions. After reviewing the consistency and cleanliness of the datasets, each were transformed and then merged to create a complete dataframe of movies with ratings. PostgreSQL, a free and open-source relational database management system (RDBMS) was used to create a database called movie-data. The cleaned, complete dataframe was then loaded into the PostgreSQL database using sqlalchemy. For reference, the original movie ratings.csv was also loaded into PostgreSQL as another table.

### By doing this ETL process manually, a greater understanding of data pipelines was understood as well as the usefullness of pandas and regular expressions for transformations.
