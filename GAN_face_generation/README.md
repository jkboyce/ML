# GAN Face Generation project

This was a second project to build a GAN, this time generating human faces by training on the [CelebA dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html). CelebA is comprised of roughly 200k images of celebrities, annotated with attributes like "wavy hair" or "bangs". Here we ignore the attribute information and use the images to train our GAN.

The generator network has three convolutional transpose layers, leading to a final output layer with tanh outputs (28x28x3 of them).

One of the challenges with GANs is quantifying the output result. With a classifier the figure of merit is classification accuracy as measured against a test dataset (not used in training): A nice concrete number. With a GAN we lack a clear metric like this, and the degree of success is a matter of human interpretation: Does the output of the generator look realistic? In this case the GAN produces recognizable faces albeit at thumbnail (28x28) resolution.
