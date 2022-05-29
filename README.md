# Project Overview
Working with the Amazing Prime Hackathon, the prupose of thius project was to create an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data. After transforming and merging data tabels were uploaded into PostgreSQL. During my analysis It utilize ETL, extract, transform and load to do the following: 
- extract and transform the Wikipedia data,
- extract and transform the Kaggle and rating data,
- load the data to a PostgreSQL Movie Database.

## Results
The ETL function takes the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates three separate DataFrames.
Then I filtered out the TV shows, consolidated the redundant data, and removed the duplicates and formatted the Wikipedia data to transform the Wikipedia data. A simialr process was conducted for the Kaggle and rating data. Again, I consolidated the redundant data, removed the duplicates, formatted and grouped the data. After the data was cleaned, I merged the data within a Wikipedia movies DataFrame. Finally, I loaded the data to a PostgreSQL Movie Database. 

![movies](https://user-images.githubusercontent.com/102122063/170889597-ed159528-0cfd-4ac9-8422-f8a33464fb38.PNG)

## Summary
The extract, transform and load function I created compelted it's prupose. It collected, organized and cleaned movie data from different sources. Wikipedia JSON and Kaggle and ratings csv files were the sources utilized. This poroicess helped make the data readble and easy to use for the Movie Hackathon and ensuing analysis. 
