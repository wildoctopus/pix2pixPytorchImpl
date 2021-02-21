# pix2pix - Pytorch Implementation
This repo is the pytorch implementation of pix2pix architecture as provided in the paper  [Image-to-Image Translation with Conditional Adversarial Networks](https://arxiv.org/abs/1611.07004)

How to use?
* Clone the repo
* Download the Maps dataset from here. [Download](http://efrosgans.eecs.berkeley.edu/pix2pix/datasets/maps.tar.gz). Extract it to root cloned folder. 
* To train, run train.py


#Architectural Details
Pix2pix architecture uses Unet architecture as a Generator and PatchGAN as a Discriminator. 


![Generator(Unet)](./images/unet.svg)
