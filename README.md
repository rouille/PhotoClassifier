# Project Overview
I wrote a small pipeline to classify user-supplied images.
* Feed the photograph of an object to a pre-trained Convolutional Neural Networks (CNN) algorithm and;
* get the top 3 most likely classes for the image and their probabilities.  

This project relies on CNN to classify images. We use the pre-trained ResNet50 model to do so. This model is trained on a subset of the [ImageNet](http://www.image-net.org/) database, which is used in the ImageNet Large-Scale Visual Recognition Challenge (ILSVRC).

# Instructions
We use the Keras framework as a deep learning library. Their  contributors keep a list of the state-of-the-art CNNs models (VGG, Inception, ResNet, ...) with their implementations and pre-trained weights on a common dataset like the ImageNet or [CIFAR](https://www.cs.toronto.edu/~kriz/cifar.html). 

Open the notebook and follow the instructions:
```
jupyter notebook classify.ipynb
```
