# Project Overview
The goal of this project is to classify images using convolutional neural networks. We have investigated three different approaches that are presented in the following notebooks:
* `scratch.ipynb`: a CNN is trained from scratch. The [CIFAR](https://www.cs.toronto.edu/~kriz/cifar.html) database is used for this purpose.
* `pre-trained.ipynb`: a photograph of an object is fed to a deep learning model and the top 3 most likely classes for the image and their probabilities are retuned.
* `fine-tuning.ipynb`: a pre-trained deep learning model is fine-tuned on a new set of classes.

The ResNet50 model is used in this project. This model is trained on a subset of the [ImageNet](http://www.image-net.org/) database, which is used in the ImageNet Large-Scale Visual Recognition Competition (ILSVRC).

# Instructions
We use the [Keras](https://keras.io/) deep learning library with TensorFlow as a backend for this project. It is worth noting that state-of-the-art models (VGG, Inception, ResNet, ...) with their implementation and pre-trained weights on common dataset like ImageNet or [CIFAR](https://www.cs.toronto.edu/~kriz/cifar.html) are easily accessible with Keras.

Open a notebook and follow the instructions. For instance:
```
jupyter notebook pre-trained.ipynb
```
