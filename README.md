# Project_Recommendation-SystemofAnime
This project is built to set up a recommendation system for anime, as well as evaluating several recommendation methods.

## Motivation.
The most important motivation of this project is to evaluate several methods of recommendation, and to select the best one in this project.

## Data source.
The data source is https://www.kaggle.com/CooperUnion/anime-recommendations-database/data, the data from kaggle competition.

## The recommendation methods in competition.
- SVD: Singular Value Decomposition.
- NMF: Negative Matrix Factorization.
- CF: Collaborate Filtering.
- DAE: Deep AutoEncoder.

## Results. 
Evaluated by RMSE.
- SVD: 1.1840
- NMF: 2.2097
- CF:
- DAE: 0.7809

The best recommendation method is DAE, according to experiment。
