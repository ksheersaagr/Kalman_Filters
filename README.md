# Implementation of Kalman_Filters
## This is the implementation of Kalman Filters, which I have implemented during my Udacity CVND program.

Kalman Filter is also considered as the linear quadratic estimation algorithm, in which a joint probability distribution over the variables for each timeframe is estimated.
The algorithm uses the new mean and new variance in order to calculate the uncertainty and tries to provide accurate measurements for each timeframe of the measurement update(sensing/prediction) and the motion update(moving).
The algorithm also uses other inaccuracies and statistical noise in order to represent the initial uncertainty.

## Kalman filter is used in localization in which a robot locates itself by moving through an unknown environment by performing a cycle of sensing/predicting and moving in that environment or world.

Autonomous Vehicles are an active field of research in which such algorithm are used where an agent predicts and move across the environemnt by judging the uncertanity in an environment.
Such algorithms are solely based on the Baye's rule.

## How to run:
open the jupyter notebook in a browser and run each cell on after the other. also, make sure to play around with the code and changing values of sig(sigma/noise/uncertainty) in order to get clear understanding of what is actually happening!
