1. Using R (with no use of special libraries), implement an SGD algorithm.

2. Now let’s study the effect of the L2 norm regularization on the training and testing errors:
  a. Load Task1C_train.csv and Task1C_test.csv sets.
  b. For each lambda in {0, 0.4, 0.8, ..., 10}, build a regression model and compute the training and testing errors, using the provided data sets. While building   each model, all parameter settings (initial values, learning rate, etc) are exactly the same, except a lambda value. Set the termination criterion as maximum of 20 x N weight updates (where N is the number of training data). Create a plot of error rates (use different colors for the training and testing errors), where the x-axis is log lambda and y-axis is the error rate.
