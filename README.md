# Project Overview
This is a collection of notebook in which we use Convolutional Neural Networks (CNNs) to classify images.
* In the first notebook (```scratch.ipynb```), a CNN is trained from scratch. The [CIFAR](https://www.cs.toronto.edu/~kriz/cifar.html) database is used for this purpose.
* A pre-trained CNN is used in the second notebook (```pre-trained.ipynb```). In that case, a photograph of an object is fed to a state of the art CNN model and the top 3 most likely classes for the image and their probabilities are retuned.
* In the third notebook (```fine-tuning.ipynb```), we fine tune a pre-trained CNN on a new set of classes.   

We use the pre-trained ResNet50 model to do so. This model is trained on a subset of the [ImageNet](http://www.image-net.org/) database, which is used in the ImageNet Large-Scale Visual Recognition Challenge (ILSVRC).

# Instructions
We use [Keras](https://keras.io/) deep learning library. Their contributors keep a list of the state of the art CNNs models (VGG, Inception, ResNet, ...) with their implementation and pre-trained weights on common dataset like ImageNet or [CIFAR](https://www.cs.toronto.edu/~kriz/cifar.html). Note that we use TensorFlow as a backend.

Open a notebook and follow the instructions. For instance:
```
jupyter notebook pre-trained.ipynb
```
