# Recommender Systems Competition @ Politecnico di Milano

<p align="center">
    <img src="https://i.imgur.com/mPb3Qbd.gif" width="180" alt="Politecnico di Milano"/>
</p>

[![open-Kaggle](https://img.shields.io/badge/open-Kaggle-4791CD.svg)](https://www.kaggle.com/c/recommender-system-2021-challenge-polimi)

The Recommender System Course at Politecnico di Milano is divided into two parts: the most important one consists in a Internal [Kaggle Competition](https://www.kaggle.com/c/recommender-system-2020-challenge-polimi) amongs students.

This repository is forked by the [official one](https://github.com/MaurizioFD/RecSys_Course_AT_PoliMi) of Polimi, developed by [Maurizio Ferrari Dacrema](https://mauriziofd.github.io/), Postdoc researcher at Politecnico di Milano. See the [website](http://recsys.deib.polimi.it/) for more information on its research group.


## The Competition

Goal:

The application domain is TV programs recommendation. The datasets we provide contains both interactions between users and TV shows, as well as features related to the shows. The main goal of the competition is to discover which items (TV shows) a user will interact with.
Each TV show (for instance, "The Big Bang Theory") can be composed by several episodes (for instance, episode 5, season 3). The goal of the recommender system is not recommend a specific episode, but to recommend the TV show.

Description:

The datasets includes around 6.2M interactions, 13k users, 18k items (TV shows) and four feature categories: 8 genres, 213 channels, 113 subgenres and 358k events (episode ids).
The training-test split is done via random holdout, 85% training, 15% test.
The goal is to recommend a list of 10 potentially relevant items for each user. MAP@10 is used for evaluation. You can use any kind of recommender algorithm you wish e.g., collaborative-filtering, content-based, hybrid, etc. written in Python.

## What you can find in this repo
 Only what is necessary to build and test the model we used to reach my best result in the competition (**8th place**).
 In particular the recommender systems algorithm that I have used:
 * EASE_R
 * SLIM elastic net
 * UserKNN collaborative filtering
 * Implicit ALS
 
## The Best Model:
 Desciption of my final (best) model: 
 
 Merge of models listed above with different weights.

## Results

* Final Deadline:
    * *public leaderboard*: **5th** position, score: 0.48641
    * *private leaderboard*: **8th** position, score: 0.48632
