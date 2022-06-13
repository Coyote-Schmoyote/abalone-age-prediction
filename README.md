# Abalone Age Prediction

A machine learning project that predicts the age of abalone mollusks 
## 1. Problem Definition

Predict the age of abalone mollusks based on the attributes.

> Age is calculated by adding +1.5 to the number of rings.

## 2. Data

The data is downloaded from the Kaggle Abalone Dataset: https://www.kaggle.com/datasets/rodolfomendes/abalone-dataset

> The dataset was donated in 1995 by S. Waugh, University of Tasmania. It is originally based on a study "The Population Biology of Abalone in Tasmania" by N. J. Wawick, T. L. Sellers, S. R. Talbot, A. J. Cawthorn and W. B. Ford (1994). The original dataset can be found here: https://archive.ics.uci.edu/ml/datasets/abalone

## 3. Features

The data consists of 9 features:

* Sex (M-Male, F-Female, I-Infant)
* Length (longest shell measurement)
* Diameter (perpendicular to length)
* Height (with meat in shell)
* Whole weight (swhole abalone)
* Shucked weight (weight of meat)
* Viscera weight (gut weight after bleeding)
* Shell weight (after being dried)
* Rings (+1.5 gives the age in years)

## 4. Approach

To solve this problem, we are going to complete the following steps:

* Explore and get familiar with the data
* Visualize data
* Model data → clean and transform data to make it suitable for machine learning
* Choose a machine learning model and train it
* Evaluate the scores
* Tune hyperparameters
* Evaluate and compare the scores
* Visualize the results
