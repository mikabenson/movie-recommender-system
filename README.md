# Building a Recommendation system: creating an item based collaborative filtering to recommend top 5 movies to users. 🚀

# Here is the link image for the Recommendation system
https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.imdb.com%2Ftitle%2Ftt27727764%2F&psig=AOvVaw3L023A39JeGvqy-cRWv8f7&ust=1739468257743000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCLD1pr3WvosDFQAAAAAdAAAAABAE

## Introduction 🌟
Here is my Phase 4 project for creating a Recommender system. I'm creating a recommender system on an item based collaborative filtering which provides top 5 movie Recommendation to users based on their ratings

## About the Challenge 🌐
Hollywood movie studio aims to enhance the user engagement and its revenue by implementing an item-based-recommender system that  suggest movies which are similar to the other users might have rated. Lets leverage the movie similarities based on the attributes like ratings and title as we seek to improve content and provide a highly personalized experience. The recommender systems built provides top 5 movie recommendations to a user, based on their ratings of other movies.


### Objectives 📝
1. Retrieve the top 5 movie title recommended to user based on their ratings

2. Enable users explore a wide range of films similar to their preferences

3. Drive users subscriptions by suggesting appealing content


## Project Files 📂

Key files related to this project:
We were provided two dataset, movies.csv, ratings.csv

## My Approach 🚀

1. **Reading Datasets**: I began by loading the provided datasets, both the rating.csv and movies.csv

2. **Handling Missing Values**: I checked missing data in the dataset, ensuring that no valuable information was lost.

3. **Creating a cleaned csv file**:  I created a cleaned csv file movie_ratings_df

4. **Data Visualization** : I perform some visualization creating a joint plot to visualize the relationship between average rating and number of ratings

5. **Preparing the data for surprise**: I prepared the data for surprise  such that the surprise library would work with (rating scale)

6. **Building the Item-Based Collaborative Filtering Model**: I built a recommender system using item based collaborative filtering using the KNNBasics and KNNBaseline then compared the RMSE performance.

7. **Creating Collaborative filtering using SVD**: I used the SVD algorithm to find the movies that the users who liked a given movie also liked

8. **Creating Functions that gives movie recommendation**: I created function to get the top 5 recommendations 

9. **Training the collaborative filtering model**: I used the function to get the top recommended movies which have similarities

11. **Conclusion and Recommendations**: I gave few conclusion and created recommendations for the top 5 movies based on some movie title.


## Connect with Me 📫

You can link with me on my github account and find more of my projects on [GitHub](https://github.com/mikabenson/movie-recommender-system)).


