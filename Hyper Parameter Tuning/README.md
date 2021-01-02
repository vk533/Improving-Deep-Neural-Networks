# Hyper Parameter Tuning
## Grid Search vs Random Search
Let’s say for a model we have more than one hyperparameter we are tuning, one hyperparameter probably will have more of an influence on train/validation accuracy than another hyperparameter. In this case, we may want to try a wider variety of values for the more impactful hyperparameter, but also at the same time, we don’t want to run too many models as it is time consuming.
For this example let us say we are optimising two different hyperparameters, α and ε. We know α is more important and needs to be tuned by trying out as many different values as possible. Then again you still want to try 5 different ε values as well. So, if I choose to try 5 different α values, that comes to 25 different models. We have run 25 models with different combinations of 5 α and 5 ε.
But we want to try more α values without increasing the number of models. For this, we use a random search, where we choose 25 different random values of each α and ε, and each pair of values is used for each model. Now we have to only run 25 models but we get to try 25 different values of α instead of the 5 we did in a grid search.

![Image](Picture1.jpeg)

