# Deep Convolutional GAN House Numbers project

This project implements a deep convolutional GAN, very similar in approach to [this paper](https://arxiv.org/pdf/1511.06434.pdf) by Radford et al (2016). The GAN is trained on the [Street View House Numbers dataset](http://ufldl.stanford.edu/housenumbers/) and many of the generated images are quite convincingly "could be real".

Training the GAN is an interesting exercise. Because of the competitive nature of the generator and discriminator, the training does not relax in a straightforward way. Even after many training epochs the network losses continue to fluctuate considerably, and for a few steps the generator will seemingly regress in the quality of its output. This and the other GAN projects gave me a healthy respect for the challenge of training these types of networks.
