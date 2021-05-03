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
![Black Blond](https://user-images.githubusercontent.com/55629156/114266376-4c894080-99f6-11eb-9aa3-3ef672f56f0b.png)

![Smile](https://user-images.githubusercontent.com/55629156/114266438-b3a6f500-99f6-11eb-9066-b0f7629757aa.png)


# Second Model : AC GAN
As a result of this model we got FID score less than 21.
In this model We use Discrimnaotr as both classfire for real and fake images and predict labels of input images.

![blonde](https://user-images.githubusercontent.com/55629156/116854606-3e46d280-abf8-11eb-9d7d-57c3cab64ef4.png)

![smile_ac](https://user-images.githubusercontent.com/55629156/114273605-05fa0d00-9a1b-11eb-9d4a-1141650f5284.png)


# Group Memebers
Saeid Amir Haftehran - saeid.amirhaftehran@studio.unibo.it 

Ali Tavana           - ali.tavana@studio.unibo.it

Maryam Alizadeh      - maryam.alizadeh@studio.unibo.it
