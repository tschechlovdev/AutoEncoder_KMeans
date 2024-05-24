# AutoEncoders for k-Means Clustering

Follow-up of [k-Means Clustering on image data](https://github.com/tschechlovdev/kmeans_MNIST).

This repository showcases how to apply Auto-Encoders to learn an easier linear separable presentation of the data.
This is especially useful for tasks like clustering. 
To this end, the famous MNIST dataset that comprises images of handwritten digits is used.
The Auto-Encoder is implemented using PyTorch and scikit-learn is used to apply clustering.

The notebook shows that the accuracy of k-Means clustering can be improved by more than 20%-points using Auto-Encoders!
