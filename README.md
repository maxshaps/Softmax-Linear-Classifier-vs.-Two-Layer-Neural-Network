# Softmax-Linear-Classifier-vs.-Two-Layer-Neural-Network

Performance comparison of a Softmax linear classification model and a two layer neural network on a generated data set.  The data set is a three class spiral data set, generated since the classes are not easily separable via linear classification.  After implementing the Softmax classification model and demonstrating its poor performance, a two layer neural network is manually implemented and shown to vastly improve accuracy on the training data.  Manual implementation of the two layer neural network requires care in correctly computing the parameter gradients via backpropagation (extensive comments provided in the Jupyter notebook), which are then used for parameter updates in the direction of the negative gradient of the loss function (loss function used here is the sum of a cross-entropy loss term and an L2 regularization loss term).



## Background

Largely inspired by the case study given in the Stanford CS231n Convolutional Neural Networks for Visual Recognition course notes: http://cs231n.github.io/
