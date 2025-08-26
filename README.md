# GenerativeAdversarialNetwork-


###GAN for Fashion Item Generation###
This project demonstrates the use of a Generative Adversarial Network (GAN) to generate realistic, grayscale images of fashion items. The model is trained on the Fashion-MNIST dataset, a collection of 28x28 pixel images of clothing and accessories.

The goal is to show a clear understanding of GAN architecture and the training process, resulting in a generator model capable of creating novel fashion designs from random noise.

Tech Stack:

-Python

-TensorFlow / Keras

-NumPy

-Matplotlib (for visualizing results)

-imageio (to create a training progress GIF)

How It Works:

The project consists of two main components:

Generator: A neural network that takes a random noise vector as input and upsamples it to create a 28x28 pixel image. It learns to produce images that can fool the Discriminator.

Discriminator: A standard Convolutional Neural Network (CNN) that is trained to distinguish between real images (from the Fashion-MNIST dataset) and fake images (created by the Generator).

These two networks are trained in an adversarial process, where the Generator gets better at creating images and the Discriminator gets better at spotting fakes.


Results:
-Increase the number of the epochs are necessary to improve the model performance with the applied dataset.
-Requires a GPU or a more hours of training to obtain a better performance.
