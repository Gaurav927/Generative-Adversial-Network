# Generative-Adversial-Network
Generative Adversial Network using MNIST Data

## Steps of GAN Algorithm

1. The generator takes in random numbers and returns an image.
2. This generated image is fed into the discriminator alongside a stream of images taken from the actual, ground-truth dataset.
3. The discriminator takes in both real and fake images and returns probabilities, a number between 0 and 1, with 1 representing a prediction of authenticity and 0 representing fake.

## Model Architecture 
![GAN](https://user-images.githubusercontent.com/21220616/55735343-c751a680-5a3e-11e9-8a15-ec8470b01085.png)

## GAN working Principle
There are 2 neural network, one neural network called generator generates new data instances while the other discriminator 
evaluates the generated image for authencity. Generators creates synthetic images and then passes to discriminator(In hope that
Generator will be able to fool the Discriminator even images generated by generator are fake.

So we have a Counter Objective function for Generator and Discriminator

**Generator is trying to fool the Discriminator while Discriminator is trying caught the fake images coming from Generator**

## Algorithm (taken from Paper)

![Algorithm_GAN](https://user-images.githubusercontent.com/21220616/55735992-1c41ec80-5a40-11e9-8b05-7bcf20b824ac.png)

![Training](https://user-images.githubusercontent.com/21220616/55737140-48f70380-5a42-11e9-8974-c52cf9fe53fe.png)

Result

![result](https://user-images.githubusercontent.com/21220616/57768740-e4f2e980-7729-11e9-94a4-556c5a252a4d.jpg)







