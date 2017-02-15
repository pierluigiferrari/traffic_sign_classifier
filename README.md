## Building a Traffic Sign Recognition Classifier

This is a Convolutional Neural Network built with TensorFlow and trained to recognize traffic signs. The dataset used is the [German Traffic Sign Recognition Benchmark](http://benchmark.ini.rub.de/?section=gtsrb) dataset.

The final model achieves an accuracy of 97.9% on the official GTSRB test dataset.

The model includes my own implementation of batch normalization using a running average estimator of the population moments, along with a few tests and visualizations to see what batch normalization does.

All code, training results, and relevant explanations and comments are contained in the iPython notebook in this directory.

The resized and pickled versions of the official GTSRB training and test datasets that were used for this project can be downloaded [here](https://drive.google.com/open?id=0B0WbA4IemlxlUmlJaDBXbzJHMFE).
