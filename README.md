# **Inpainting-GAN**

##Introduction
This project aims to implement an image inpainting technique using Generative Adversarial Networks (GANs). Image inpainting is the process of filling in missing or damaged regions in images. GANs are a type of deep learning architecture that consists of two neural networks, a generator and a discriminator, trained adversarially to generate realistic images.

##Dataset:
The Paris Street View dataset was used in this project. The dataset consists of street view images of various scenes in Paris.

##Requirements:
+ Python
+ PyTorch
+ NumPy
+ OpenCV
+ Matplotlib

##Code Structure:
+ InpaintingDataset: Custom dataset class for loading and preprocessing images for inpainting.
+ Generator: Generator network architecture for GAN.
+ Discriminator: Discriminator network architecture for GAN.
+ train_GAN: Function to train the GAN model.
+ display_images: Function to display original, masked, and generated images.
+ DisplayTest: Function to display a sample of original, masked, and generated images for visual inspection.

##Results
The trained GAN model successfully inpaints missing regions in images, producing visually plausible results in both video and stills

##Author:
Adriteyo Das, Engineering Student @MIT Manipal. 

##Acknowledgements
Special thanks to Dr. Deepak Pathak for providing access to the Paris Street View dataset, which was instrumental in the completion of this project.



