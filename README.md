# Image Generation with Autoencoder and GAN AI Networks.
I made this with my classmate Weronika as a final project for my Uni class "Introduction to Artificial Intelligence". This has been a fun class and I hope this project shows that :)
We used Tensorflow and Keras.

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

# Results:

Our Classes in the training set (we can see nice separation):
![DataClasses](https://user-images.githubusercontent.com/112573508/215481439-1e5220cf-300c-4ba1-98ed-4d8cd486498e.png)

Generated Images:
![genImgClasses](https://user-images.githubusercontent.com/112573508/215483065-72e2dcdd-72cb-4c0c-a1f0-e6073e780df8.jpg)


Noise reduction with the Autoencoder:
![noise](https://user-images.githubusercontent.com/112573508/215482568-1ffdd3ff-8bc8-4d5c-a029-05c4264163cc.jpg)
![noisereduction](https://user-images.githubusercontent.com/112573508/215482811-10d9a383-1b45-4ba6-8095-d8f2fdf50226.jpg)

Results of GAN generation:
![GAN_generated](https://user-images.githubusercontent.com/112573508/215483479-ae63360b-7656-4140-86f1-15b58947c828.gif)
