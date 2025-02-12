# Fashion-MNIST-Image-Generation-using-GANs-and-LSGANs

Project Overview

This project explores GANs and Least Squares GANs (LSGANs) using PyTorch for image generation on the Fashion MNIST dataset. 

The workflow includes:
Implementing a GAN to generate realistic images from random noise.
Training and fine-tuning the model to improve image quality.
Saving and loading model weights for experimentation.
Comparing standard GAN vs. LSGAN results.

Dataset

The project utilizes Fashion MNIST, which consists of grayscale images of clothing items across 10 categories.

Model Training Workflow

1.GAN Implementation:
Load the Fashion MNIST dataset,
Create a Generator and Discriminator network with CNN-based architecture,
Train the GAN model to generate realistic images,
Saving and visualize at least 3 generated samples,
Saving the model weights for later use,
Loading the saved model and continue training to improve results.

2.LSGAN Implementation:
Modify the loss function from Binary Cross-Entropy (BCE) to Least Squares loss,
Repeat the training steps from GAN, but now with LSGAN loss,
Compare the quality of generated images between GAN and LSGAN.

Results:
Comparison between Standard GAN and LSGAN.
Generated images from both models are visualized.
Analysis of training stability and convergence is provided.
