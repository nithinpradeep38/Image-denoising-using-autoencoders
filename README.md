# Image-denoising-using-autoencoders

#### Use a few variants of auto-encoders for de-noising the images.

Autoencoders can be used for image denoising by training the network to learn a compressed representation of the input image and then reconstruct the image from this representation.

During training, the autoencoder is fed with pairs of noisy images and clean images. The objective is to minimize the difference between the noisy input image and the clean target image. The autoencoder consists of two main parts: an encoder and a decoder. The encoder compresses the input image into a lower-dimensional representation, while the decoder reconstructs the image from this representation.

In the given problem, we have the dataset of emergency and non-emergency vehicles. The train dataset has noisy and clean data. We use this to train our autoencoder, followed by predicting on the noisy test dataset.

We have tested the U-net architecture of autoencoder on this problem to achieve decent results. 
