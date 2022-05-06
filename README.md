# Analysis-Helper

## What is it for?
* These notebooks were created to enable a research lab to carry out a machine learning process in python without necessarily enlisting a programmer.
* The main notebook is designed as a register of the machine learning process used to create the current model, an SVM model with an RBF kernel.
* It was made in case the researches obtain more data, so that they can check its distribution and use it to retrain the model.

## Modules
* The Analysis Helper - the main module, a register of the entire process with visualizations.
* Functional Modules - machine learning algorithms and sanity checks, divided by their contents:
  * obtainingTheData
  * exploringTheRankings
  * predictionModel 

## How to run
Run the main module. First cell will import the other necessary modules.

## Table of Contents
1. Obtaining the data
     a. Imports
     b. Reading the file
     c. Feature extraction
     d. Binarification
     e. Missing values
     f. Scaling
     g. Outliers
2. Exploring the rankings
     a. Ranking table
     b. Object popularity
     c. Clustering
     d. Cluster popularity
3. Prediction model
     a. Initial run
     b. Feature selection
     c. Hyperparameter tuning
     d. Model significance
     e. Final run
