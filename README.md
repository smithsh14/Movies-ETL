# Movies-ETL
Module 8 Lesson

## Overview of the Project
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

### Required Deliverables
For this project there are four deliverables for analysis...
- Deliverable 1: Write an ETL function to read three data files
- Deliverable 2: Extract and Transform the Wikipedia Data
- Deliverable 3: Extract and Transform the Kaggle Data
- Deliverable 4: Create the Movie Database

#### Deliverable 1
Task: Using your knowledge of Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.
- Resulting file for Deliverable 1 can be found under ETL_function_test.ipynb.

#### Deliverable 2
Task: Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.
- Resulting file for Deliverable 2 can be found under ETL_clean_wiki_movies.ipynb.

#### Deliverable 3
Task: Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.
- Resulting file for Deliverable 3 can be found under ETL_clean_kaggle_data.ipynb.

#### Deliverable 4
Task: Use your knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
- Resulting file for Deliverable 4 van be found under ETL_create_database.ipynb.
- Additionally, screenshots for the movies query and the ratings query can be found in the Resources folder. 
