# Player Feedback Analysis in Video Games

## Problem

What drives user engagement and positive feedback in video games?

This project analyzes a large-scale Steam dataset to identify which game characteristics influence the number of positive user reviews.

## Dataset

* \~100,000 Video Games live on steam
* Features include

  * Median Playtime
  * Price
  * Genres
  * Release date
  * etc.

The dataset is highly skewed and zero-inflated, reflecting real-world platform dynamics.

## Approach

* The data was cleaned and pre-processed
* Log transformations for skewed variables
* Feature engineering
* Correlation analysis
* Simple and multiple linear regression models
* Realistic data was preserved

## Key findings

* Playtime is the strongest predictor of user engagement
-R² ≈ 0.43 (alone)
* Full regression model explains \~50% of variance
* Achievements and certain genres (Action, RPG, Simulation) are positively associated with engagement
* Price has minimal impact when other factors are controlled
* Release year shows negative relationship
→ older games accumulate more reviews over time

## Limitations

* Observational data
* Missing variables
* Heavy skew and zero-inflation challenge standard models
* Study of only one platform

