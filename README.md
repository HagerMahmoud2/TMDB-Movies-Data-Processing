# TMDB-Project_Overview

This project focuses on analyzing movie data from The Movie Database (TMDB) using PySpark. The dataset contains information about nearly 5000 movies, including details such as budget, genres, original language, popularity, release date, and more.

## Key Features:

- **Data Loading:**  
  The project involves loading the TMDB dataset from a CSV file into HDFS (Hadoop Distributed File System) and then reading it using PySpark to begin processing.  

- **Pre-Aggregation:**  
  Pre-aggregated tables are created to summarize movie data by genres and identify the most popular film in each original language.  

- **PySpark Implementation:**  
  The entire project is implemented using PySpark, a Python API for Apache Spark, which provides distributed processing capabilities for large-scale data analysis.  

## Deliverables:

- **PySpark Code:**  
  Scripts for creating pre-aggregated tables and populating them.  

- **Genres_Aggregations.csv:**  
  Pre-aggregated table saved in HDFS containing genre-wise statistics such as genre ID, name, and number of movies.  

- **popular_film_per_lan.csv:**  
  Pre-aggregated table saved locally, listing the most popular film in each original language.  

## Technologies Used:

- **PySpark**  
- **Hadoop Distributed File System (HDFS)**  
