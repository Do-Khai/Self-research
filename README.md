# HandWritting Digit Recognition using 2 different methods: SVM and CNN

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.10](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/downloads/release/python-360/) 
![0](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEh4bTijB6fd47hlvs6sHKU9atqJFtvvhzd7NI8jjuK-spj8L5WuBztWzIKUhsDOHVeCnY0hihww9RBVJebjclPz8E609p5AH-5zhmXt4f5omdN50PU2WhZfCSV68_tQBCtKYayYFBOjw-BClnrL2jKKmTjnZbaNAhzRFsnZiUfwByPu5ZkrguGQ8yQD5A/w0/20220527_202930_0000.png)


## Overview
- Support Vector Machines (SVM) can be used for MNIST by transforming the image pixels into feature vectors and applying SVM classification. Each image is flattened into a vector, and SVM finds an optimal hyperplane to separate the different digit classes based on these feature vectors. SVM's ability to handle high-dimensional data makes it suitable for the task. However, SVM may require careful selection of hyperparameters and feature scaling to achieve good performance.
- Convolutional Neural Networks (CNN) are widely used for MNIST handwriting recognition. CNNs process the 2D image structure directly without explicit feature engineering. They use convolutional layers to extract local patterns and spatial relationships from the images, and pooling layers to downsample the spatial dimensions. Fully connected layers perform classification based on the learned features. CNNs excel at capturing intricate details and achieving high accuracy on the MNIST task. They can be trained end-to-end, automatically learning relevant features for digit recognition.

For more information, please check [my self-research paper](https://github.com/Do-Khai/Self-research/blob/main/Handwriting-recognition.pdf).

## MNIST Dataset
![0](https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/MnistExamples.png/320px-MnistExamples.png)

MNIST is a collection of handwritten digits from 0-9. Image of size 28 X 28

## Requirements
- Python 3.5 +
- Scikit-Learn (latest version)
- Numpy (+ mkl for Windows)
- Matplotlib
- Keras

