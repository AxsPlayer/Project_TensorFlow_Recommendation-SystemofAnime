# Project_Recommendation-SystemofAnime
This project is built to set up a recommendation system for anime, as well as evaluating several recommendation methods.

## Motivation.
The most important motivation of this project is to evaluate several methods of recommendation, and to select the best one in this project.

# Content of Project.
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

The best recommendation method is DAE, according to experiment.

# Structure of Project.
## Data exploration.
- data_analysis.ipynb: This script is used to explore the data, including distribution of all the features.

## Configuration.
- data: This file is created to store the anime rating data, downloaded from url given above.
- model: This file is created to save model in TensorFlow model training process.
- paper: This file is created to save papers which are helpful to deal with some problems in RecSys.

## Algorithm.
- recommendation_DAE.ipynb: This notebook contains DAE recommendation system, using TensorFlow, as well as the RMSE result.
- recommendation_basic.ipynb: This notebook contains [SVD, NMF] recommendation system, using "Suprise"(Python Package designed for RecSys algorithms), as well as the RMSE result.



