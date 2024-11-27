# Movie-Recommendation-System-using-ML

This project demonstrates a basic recommendation system using Python and pandas. The recommender system suggests movies based on similarity to other movies. While it’s not state-of-the-art, it provides a good foundation for understanding collaborative filtering and correlation-based recommendation systems.


## Overview  
In this project, we:  
1. Used movie ratings data to recommend similar movies.  
2. Explored the dataset to find patterns in ratings.  
3. Created a user-movie matrix to compute correlations between movies.  
4. Recommended movies based on their correlation scores and minimum review counts.

---

## Dataset  
The project uses two datasets:  
1. **Movie Ratings Dataset**: Contains user ratings for movies.  
2. **Movie Titles Dataset**: Contains movie titles and corresponding IDs.  

Both datasets were merged for analysis and modeling.


## Exploratory Data Analysis
We performed the following:

1. Calculated average ratings for each movie.
2. Counted the number of ratings per movie.
3. Visualized distributions of ratings and number of reviews using matplotlib and seaborn.

## Building the Recommender System
Steps:
1. Created a user-movie ratings matrix using a pivot table.
2. Calculated pairwise correlations between movies using the corrwith method.
3. Filtered movies with fewer than 100 ratings to ensure meaningful recommendations.
4. Generated recommendations for specific movies such as "Star Wars (1977)" and "Liar Liar (1997)".

## Results
Example Recommendations:

Movies similar to Star Wars (1977):

1. Empire Strikes Back, The (1980)
2. Return of the Jedi (1983)
3. Raiders of the Lost Ark (1981)
4. Austin Powers: International Man of Mystery (1997)

Movies similar to Liar Liar (1997):

1. Batman Forever (1995)
2. Mask, The (1994)
3. Down Periscope (1996)
4. Con Air (1997)
