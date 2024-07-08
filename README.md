# BYOMLP

Built a from scratch neural network using only numpy

mlp.py - adds layers to network, forward and backward prop, step and zero grad
DiscTest.ipynb - My first test of the network. Runs stochastic gradient descent to linearly separate points from around a circular disc
Classification.ipynb - Uses stochastic gradient descent to classify the digits in the MNIST dataset with 96% accuracy
Autoencoder.py - Creates a convolutional autoencoder that displays a 2d visualization of the latent space of the MNIST dataset

TODO

fix bugs in the autoencoder, loss is not going down
wrap each layer in a dictionary to avoid magic indices 
