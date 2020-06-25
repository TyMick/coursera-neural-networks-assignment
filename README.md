# Assignment: Build a Regression Model in Keras

This assignment was the final project in IBM's [Introduction to Deep Learning & Neural Networks with Keras](https://www.coursera.org/account/accomplishments/certificate/QQEVGBYCHYYP) course on Coursera. The objective: build a regression model to predict the compressive strength of concrete based on its age (in days) and the volumes of the different ingredients used to make it.

Each part of the assignment involved the following steps:

1. Randomly split the data into training and test sets, holding 30% for testing.
2. Build a neural network with hidden layers of 10 nodes each, using ReLU activation, Adam optimization, and a mean squared error loss function.
3. Train the model over a certain number of epochs.
4. Evaluate the model on the test data and compute the mean squared error between the predicted strength and actual strength.
5. Repeat the previous steps 50 times.
6. Report the mean and the standard deviation of the 50 mean squared errors.

The four parts differed as follows in terms of whether or not the input data was normalized, the number of hidden layers, and the number of epochs over which the model was trained:

- **Part A**: raw input data, 1 hidden layer, 50 epochs
- **Part B**: normalized input data, 1 hidden layer, 50 epochs
- **Part C**: normalized input data, 1 hidden layer, 100 epochs
- **Part D**: normalized input data, 3 hidden layers, 50 epochs

Take a look at the [`complete_writeup` notebook](/complete_writeup.ipynb) for the full story—it contains all four parts.
