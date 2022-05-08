# Analysis-Helper

## What is it?
* These notebooks were created to enable a research lab to carry out a machine learning process in python without enlisting a programmer.
* The main notebook is designed as a register of the machine learning process used to create the current model, an SVM model with an RBF kernel.
* It was made in case the researches obtain more data, so that they can check its attributes and use it to retrain the model.

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
  * Imports
  * Reading the file
  * Feature extraction
  * Binarification
  * Missing values
  * Scaling
  * Outliers
2. Exploring the rankings
  * Ranking table
  * Object popularity
  * Clustering
  * Cluster popularity
3. Prediction model
  * Initial run
  * Feature selection
  * Hyperparameter tuning
  * Model significance
  * Final run
