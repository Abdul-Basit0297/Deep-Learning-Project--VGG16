# Deep-Learning-Project--VGG16

VGG16 Implementation with TensorFlow and Keras

Overview:
This repository contains the implementation of the VGG16 (Visual Geometry Group 16) model using TensorFlow and Keras for image classification tasks. VGG16 is a convolutional neural network architecture proposed by the Visual Geometry Group at the University of Oxford, known for its simplicity and effectiveness in image recognition tasks.

Dataset:
The model is trained and evaluated on various image datasets CIFAR-100.

Model Architecture:
The VGG16 model architecture consists of 16 layers, including 13 convolutional layers and 3 fully connected layers. The convolutional layers are stacked on top of each other, with small 3x3 filters and a stride of 1. Max-pooling layers are used to downsample the feature maps. The fully connected layers are followed by softmax activation for classification.

Dependencies:

Python
TensorFlow
Keras
NumPy
