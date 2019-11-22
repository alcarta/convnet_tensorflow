# ConvNet applications using TensorFlow 2.0
This repo contains notebooks about the Coursera course "Convolutional Neural Networks in TensorFlow"

## Image Augmentation
Overfitting is simply the concept of being over specialized in training -- namely that your model is very good at classifying what it is trained for, but not so good at classifying things that it hasn't seen. In order to generalize your model more effectively, you will of course need a greater breadth of samples to train it on. That's not always possible, but a nice potential shortcut to this is Image Augmentation, where you tweak the training set to potentially increase the diversity of subjects it covers.

The (Cats_vs_Dogs_using_augmentation.ipynb)[Cats_vs_Dogs_using_augmentation.ipynb] contains an example of apllication of the ImageAugmentation class on the Cats-vs-Dogs dataset.
