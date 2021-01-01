# Improving Deep Neural Networks
Hyper Parameter Tuning, Gradient-Checking and Regularization
## Hyper Parameter tuning : 
Here are a few popular hyperparameters that are tuned for deep networks

- α (alpha): learning rate
- β (beta): momentum
- number of layers
- number of hidden units
- learning rate decay
- mini-batch size

There are others specific to optimisation techniques, for instance, you have β1, β2, and ε for the Adam optimisation.
PLease feel free to check the Hyper Parameter Tuning dicectory for detailed description

## Regularization : 
Overfitting can be a huge problem with models due to high variance, this can be solved by getting more training data, but that’s not always possible, so a great alternative is regularisation. Check the Regularization directory for detailed description.

## Gradient Checking : 
Gradient Checking is basically approximating the gradient using a numerical approach. If it is close to the calculated gradients, then backpropagation was implemented correctly! More details in the Gradient Checking directory.
