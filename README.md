# Generating Synthetic Plant Images using GAN's

## Introduction
Deep Convolutional Generative Adversarial Networks (DCGAN) are trained on plant images and used the trained model to generate synthetic plant images. In this project DCGAN is trained and evaluated on images from [64 x 63 x 3] upto [1536 x 156 x 3]. Along with StyleGAN3 is also implemented for image generation.

## DataSet Preparation
### Foreground segmentation using instance segmentation masks
<div style="text-align: center;">
    <img src="DCGAN/imageProcessing/original.png" width=300 alt="original Image" >
    <img src="DCGAN/imageProcessing/instance.png" width=300 alt="Insance Image" >
    <img src="DCGAN/imageProcessing/gray.png" width=300 alt="Grayscale Image" >
    <img src="DCGAN/imageProcessing/segmented.png" width=300 alt="Segmeneted Image" >
    <img src="DCGAN/imageProcessing/final.png" width=280 alt="Final Cropped Image" >
</div>
<p style="text-align: centre;"> (a) Original Image (b) Instance Segmentation of Original Image (c) Grayscale image of Instance segmentation image (d) Foreground Segmented Image (e) Final Cropped Image</p>

### Foreground Segmentation using Hsv color conversion
<div style="text-align: center;">
    <img src="DCGAN/imageProcessing/original.png" width=300 alt="original Image" >
    <img src="DCGAN/imageProcessing/hsv.png" width=300 alt="Insance Image" >
    <img src="DCGAN/imageProcessing/mask.png" width=300 alt="Grayscale Image" >
    <img src="DCGAN/imageProcessing/final_image.png" width=300 alt="Segmeneted Image" >
</div>
<p style="text-align: centre;"> (a) Original Image (b)Image converted to HSV color scale from RBG (c) Extract plant mask based on color range  (d) Bitwise multiply original image and plant mask</p>


## Generated Images from DCGAN
### Generated Images for 1536 X 1536 dimension
<div style="text-align: center;">
    <img src="DCGAN/imageProcessing/1536_1.png" width=300 alt="1536 Image" >
    <img src="DCGAN/imageProcessing/1536_2.png" width=300 alt="1536 Image" >
</div>

### Generated Images for 1024 X 1024 dimension
<div style="text-align: center;">
    <img src="DCGAN/imageProcessing/1024_1.png" width=280 alt="1024 Image" >
    <img src="DCGAN/imageProcessing/1024_2.png" width=280 alt="1024 Image" >
</div>

### Generated Images for 256 X 256 dimension
<div style="text-align: center;">
    <img src="DCGAN/imageProcessing/256_1.png" width=140 alt="256 Image" >
    <img src="DCGAN/imageProcessing/256_2.png" width=140 alt="256 Image" >
</div>

### Generated Images for 64 X 64 dimension
<div style="text-align: center;">
    <img src="DCGAN/imageProcessing/64_1.png" width=100 alt="64 Image" >
    <img src="DCGAN/imageProcessing/64_2.png" width=100 alt="64 Image" >
</div>

## Generated Images from StyleGAN3
### 256 X 256 Image dimensions
<div style="text-align: center;">
    <img src="styleGAN3/images/256_1.png" width=280 alt="256 X 256 Images">
    <img src="styleGAN3/images/256_4.png" width=280 alt="256 X 256 Images">
    <img src="styleGAN3/images/256_5.png" width=280 alt="256 X 256 Images">
    <img src="styleGAN3/images/256_6.png" width=280 alt="256 X 256 Images">
</div>

### 512 X 512 Image dimensions
<div style="text-align: center;">
    <img src="styleGAN3/images/512_1.png" width=350 alt="256 X 256 Images">
    <img src="styleGAN3/images/512_4.png" width=350 alt="256 X 256 Images">
    <img src="styleGAN3/images/512_5.png" width=350 alt="256 X 256 Images">
    <img src="styleGAN3/images/512_6.png" width=350 alt="256 X 256 Images">
</div>

# Model Architecture
## Generator and Discriminator Architecture
<div style="text-align: center;">
    <img src="DCGAN/imageProcessing/GAN_architecture.png" width=500 alt="GAN architecture" >
</div>

## Author
> Jayanth Somashekaraiah \
> Universität Bremen, Bremen\
> Email: jayanth@uni-bremen.de
