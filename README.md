# Introduction:
I made this with my classmate Weronika as a final project for my Uni class "Introduction to Artificial Intelligence". This has been a fun class and I hope this project shows that :)

### What is it about?
Data generation is a process in which a trained neural network, given noise as input, generates original images based on the patterns it has learned. In our case, we use an autoencoder first and then generative adversarial networks (GANs) to create images.

### What networks do we use:
**Autoencoders** are neural networks capable of learning the representations of input data, in our case, images from the input data set. When given noise or a black image as input, they are able to recreate images similar to those they were trained on.

**GAN Networks** work a bit differently, as they learn images in pairs. The generator initially generates rather weak images and the discriminator evaluates the similarity of the generated images to the data set. With each learning epoch, the generator adapts to better "trick" the discriminator until the latter cannot distinguish the generated images from the test images.

### Our goal:
The goal of the project is to create an autoencoder and GAN network to generate images of clothes and shoes based on the "Fashion MNIST" data set.

### Data set:
Fashion MNIST is a set of Zalando clothing and shoe images consisting of a training set of 70,000 images. The training set contains 60,000 images and the test set contains 10,000 images. Each example is a 28x28 grayscale image associated with a label of 10 product classes.
> https://www.kaggle.com/datasets/zalando-research/fashionmnist
