# GAN Implementation 

## Project Overview

This project implements a  Generative Adversarial Network (GAN) using PyTorch to generate human face images.

## Dataset Used
About Dataset : https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

Dataset :  https://drive.google.com/drive/folders/0B7EVK8r0v71pTUZsaXdaSnZBZzg?resourcekey=0-rJlzl934LzC-Xp28GeIBzQ

* CelebA (CelebFaces Attributes Dataset)
* Images are preprocessed to 64×64 resolution
* RGB face images are used for training


## Learning Outcomes

* Understanding GAN architecture
* Working with Generator and Discriminator networks
* Image preprocessing using Torchvision
* Training adversarial networks
* Generating synthetic face images from random noise

## Model Architecture

### Generator

* Fully Connected Neural Network
* Input: 100-dimensional noise vector
* Output: 64×64 RGB image

### Discriminator

* Fully Connected Neural Network
* Input: 64×64 RGB image
* Output: Probability of image being real or fake



