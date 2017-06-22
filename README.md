## Building a Traffic Sign Recognition Classifier

This is a Convolutional Neural Network built with TensorFlow and trained to recognize traffic signs. The dataset used is the [German Traffic Sign Recognition Benchmark](http://benchmark.ini.rub.de/?section=gtsrb) dataset.

### Training and Experimentation Results

The final model achieves an accuracy of 97.9% on the official GTSRB test dataset.

The model includes my own implementation of batch normalization using a running average estimator of the population moments, along with a few tests and visualizations to see what batch normalization does.

All code, training results, and relevant explanations and comments are contained in the iPython notebook in this directory.

### Use Instructions

1. Clone or fork this repository.
2. Launch the Jupyter notebook: `jupyter notebook traffic_sign_classifier.ipynb`
3. Execute the code cells you are interested in. Note that cells may depend on previous cells and/or require the dataset linked below. The notebook explains clearly what each code cell does.

### Dataset

The resized and pickled versions of the official GTSRB training and test datasets that were used for this project can be downloaded [here](https://drive.google.com/open?id=0B0WbA4IemlxlUmlJaDBXbzJHMFE).

### Dependencies

1. Python 3.x
2. TensorFlow 0.1x
4. Numpy
5. OpenCV
6. Matplotlib

Note: TensorFlow 1.0 introduced major syntax changes and this program does not yet support these changes.
