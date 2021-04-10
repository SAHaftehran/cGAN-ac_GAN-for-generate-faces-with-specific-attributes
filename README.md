# cGAN-ac_GAN-for-generate-faces-with-specific-attributes
This repository is our project work for Deep Learning course in university of Bologna.


In this Project we use two difrent model for training our model.
1. cGAN
2. ac_GAN

# Requirements
All you need for running this code is a gmail account for Colab and kaggle account for CelebA Data Set.

## Intruduction
Generative Adversarial Networks, or GANs for short, are a deep learning technique for training generative models. While GANs are capable of generatin plausible
images but we dont have any control in type of images that are generated.

Conditional GAN, or cGAN for short, is type of a GAN that involves the conditional generation of images by a generator model.

This networs architect consist of two model named: **Discrimnator** and **Generator**.


**The _generator_ model is responsible for generating new plausible examples that ideally are indistinguishable from real examples in the dataset.**


**The _discriminator_ model is responsible for classifying a given image as either real (drawn from the dataset) or fake (generated).**

# First Model : Conditional GAN
 As a result of this model we got 108.62 for FID score.
 

