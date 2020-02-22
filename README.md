# Machine Learning - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

In order to process this data, need to create machine learning models capable of classifying candidate exoplanets from the raw dataset.

* Steps

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

### Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

### Reporting

* Comparison of each model's performance as well as a summary about the findings and assumptions made based on the models 

## Random Forest Model
* Best Score: 0.8930001907304979 
* Random Forest model's best score of (0.8930001907304979) seems better than SVM model (0.8706847224871257) with hyperparameter tuningwhen comparing the scores.


## Neural Networks and Deep Learning Models
* The accuracy of Neural Networks model and Deep Learning model is quite close without hyperparameter tuning and less training.
Neural Network model: 0.8758581280708313
Deep Learning model:  0.8747139573097229 

## SVM Model
* Best Score: 0.8706847224871257 

## KNN Model
* Best Grid Score: 0.8489414457371733

- - -


* From observation, Random Forest model is better at predicting new exoplanets with confirmed f1- score at 0.81 while SVM model is 0.78 and KNN model is 0.72.

* All the models are good for predicting FALSE POSITIVE well with f1-score closer to 1 (0.99).

* Same comparison for Candidate - Random Forest model F1 -score is higher than other model.

- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

#####  Funke Olaleye Data  Analytics and Visualization.
