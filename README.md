I have developed a Bayesian linear regression model from scratch using numpy for predicting concrete strength. **No machine learning libraries (Tensorflow/Pytorch etc)** were used
I have developed three models one trained using maximum likelihood, and the other two trained using Bayesian inference.
For one of the Bayes model I have assumed a Gaussian prior over the weights and used evidence approximation to evaluate the hyper-parameters of the model
Consequently the posterior distribution was a Gaussian.
The other Bayes model involves a Gaussian prior over the weights and gamma prior over the variance (conjugate gaussian gamma prior). 
Consequently the posterior distribution was a gaussian gamma distribution
For both the models, the predictive distribution was evaluated (Gaussian and Student's t distribution) and plotted with matplotlib
Results of all three models were compared using root-mean-squared error function. For both he Bayes models, the point estimate for the weights were the Maximum a posteriori.
I have derived all the relevant equations and stated them in my Jupyter Notebook file
The dataset used: https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength
