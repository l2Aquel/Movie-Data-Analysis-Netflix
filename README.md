# Movie-Data-Analysis-Netflix

## Project Overview
This project involves an exploratory data analysis (EDA) of a movie dataset using Python. The primary goal is to uncover key insights related to movie genres, popularity, and trends over time.

## Files Included
movie_data_analysis_netflix.ipynb: The Jupyter Notebook containing the Python code for data loading, cleaning, analysis, and visualization.
mymoviedb.csv: The raw dataset used for the analysis.

## Dataset Description
The mymoviedb.csv dataset contains information about movies, including the following columns:
-Release_Date: The release date of the movie.
-Title: The title of the movie.
-Overview: A brief summary of the movie.
-Popularity: A metric indicating the popularity of the movie.
-Vote_Count: The number of votes received.
-Vote_Average: The average vote score.
-Original_Language: The original language of the movie.
-Genre: The genre(s) of the movie.
-Poster_Url: The URL to the movie's poster.
The dataset consists of 9827 rows and 9 columns.

## Technologies Used
-Python
-Pandas
-Numpy
-Matplotlib
-Seaborn

## Data Preprocessing and Cleaning
-The notebook includes the following data preprocessing steps:
-Casting the Release_Date column to datetime format and extracting only the year.
-Dropping irrelevant columns such as Overview, Original_Language, and Poster_Url.
-Categorizing the Vote_Average column into popular, average, below_avg, and not_popular to facilitate analysis.
-Splitting the Genre column (which contains comma-separated values) into individual genres to allow for analysis per genre.

## Key Questions & Insights
-The analysis in this project addresses several key questions:
-Most Frequent Genre: Drama is identified as the most frequent genre in the dataset, appearing in over 14% of movies.
-Highest Voted Genre: Drama also has the highest popularity among fans, accounting for over 18.5% of movies with a popular vote.
-Most Popular Movie: "Spider-Man: No Way Home" is the movie with the highest popularity rate, belonging to the Action, Adventure, and Science Fiction genres.
-Lowest Popular Movie: "The United States and Thread" has the lowest popularity rate, with genres including Music, Drama, War, and Sci-fi.
-Year with Most Films: The year 2020 saw the highest number of filmed movies in the dataset.
