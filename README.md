# Project Overview
This is a collection of notebook in which we use Convolutional Neural Networks (CNNs) to classify images.
* In the first notebook (```scratch.ipynb```), a CNN is trained from scratch. The [CIFAR](https://www.cs.toronto.edu/~kriz/cifar.html) database is used for this purpose.
* A pre-trained CNN is used in the second notebook (```pre-trained.ipynb```). In that case, a photograph of an object is fed to a state of the art CNN model and the top 3 most likely classes for the image and their probabilities are retuned.
* In the third notebook (```fine-tuning.ipynb```), we use transfer learning to classify dog breeds images. We calculate the bottleneck features of a pre-trained CNN and fine-tuned the pre-trained weights.    

We use the pre-trained ResNet50 model to do so. This model is trained on a subset of the [ImageNet](http://www.image-net.org/) database, which is used in the ImageNet Large-Scale Visual Recognition Challenge (ILSVRC).

# Instructions
We use the Keras framework as a deep learning library. Their contributors keep a list of the state-of-the-art CNNs models (VGG, Inception, ResNet, ...) with their implementations and pre-trained weights on a common dataset like the ImageNet or [CIFAR](https://www.cs.toronto.edu/~kriz/cifar.html). Note that we use Tensorflow as a backend.

Open a notebook and follow the instructions. For instance:
```
jupyter notebook pre-trained.ipynb
```
