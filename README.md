# Investigating Fandango Movie Ratings

**Introduction**

Fandango is a digital site selling movie tickets, providing movies' information and ratings.

According to Walt Hickey, the actual rating for movies on Fandango website is almost always rounded up nearest half-star. For instance, 4.1 stars will be rounded to 4.5. This rating system does not truly reflect reviewers' evaluation.

Walt Hickey published an article about his analysis and findings in Oct 2015, you can find it [here](https://fivethirtyeight.com/features/fandango-movies-ratings/).

In the response from Fandango's official, the round-up issue happened because of a bug. They promised to fix this issue.

**Goal**

The initial goal of this project is to analyse the movie ratings in the following year (2016) to see if any changes made. We are interested in analyzing the difference in the rating system of movies on Fandango websites before and after the publication of Hickey's analysis.

However, the data sets we have are not good representative of our interests. We changed our goal to better fit the data sets we have for the sake of this practice. 

New goal: the difference in ratings pattern of *popular movies* in 2015 and 2016.

**Data sets**
Hickey's dataset in [2015](https://github.com/fivethirtyeight/data/tree/master/fandango)
Dataquest's dataset in [2016](https://github.com/mircealex/Movie_ratings_2016_17)
