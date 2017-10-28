# MapReduce-RecommenderSystems

## Movie Recommender System project

### Overview

This Item based collabrative filtering recommender Systems helps people find movies that may interest them.

Main Steps

Data preprocessing

#### Raw data is from Netflix Prize Challenge

I preprocessed the original dataset in two steps:

*Change the data in each movie file into the following format: UserID, MovieID, Rating.

*Merge 17770 movie files into one big input file since Hadoop is not good for dealing with lots of small files. And the big input file is the input of our recommender system.

steps:

*Divide data by user id
*Build co-occurrence matrix
*Normalize the co-occurrence matrix
*Build rating matrix
*Multiply co-occurrence matrix and rating matrix
