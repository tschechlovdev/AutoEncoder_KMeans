# Implementation of Auto-Encoders for k-Means Clustering

This is the implementation of my medium article ["Deep Auto-Encoders for Clustering: Understanding and Implementing in PyTorch"](https://medium.com/@tschechd/deep-auto-encoders-for-clustering-understanding-and-implementing-in-pytorch-8cc748a5fa48). 

This repository showcases how to apply Auto-Encoders to learn a lower-dimensional and easier separable presentation of the data.
This is especially useful for tasks like clustering.
To this end, the well-known MNIST dataset that comprises images of handwritten digits is used.
The Auto-Encoder is implemented using PyTorch and scikit-learn is used to apply clustering.

The notebook shows that the accuracy of k-Means clustering can be improved by more than 20%-points using Auto-Encoders!
