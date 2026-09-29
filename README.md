# netflix-data-analysis

In this project I used a dataset from Kaggle and attempted to answer a few questions.
This project involves using pandas.

## **Dataset**: [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## **Notebook**: [View notebook](notebook/netflix_analysis.ipynb)

## How I prepared the dataset:
- Handling missing values in columns like director, cast, and country
- Converting the date_added column from strings to actual datetime objects
- Using .str.split() or string methods to convert countries to a list object then using the explode function to credit each country for a co-production

## Questions I answered:
- Finding out all movies released after 2015 produced specifically in "India" or the "United States"
- Determining which years saw the highest number of releases
- Finding out which countries produce the most TV shows versus movies and plotting graphs to show it
- Analyzing individual genres in the listed_in column
- Finding out the lead actor from the cast members
