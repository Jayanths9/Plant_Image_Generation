# Synthetic Generation of Plant Dataset Using GANs
## DataSet Preparation
### Foreground Segmentation using Instance Segmentation
<div style="text-align: center;">
    <img src="imageProcessing/original.png" width=300 alt="original Image" >
    <img src="imageProcessing/instance.png" width=300 alt="Insance Image" >
    <img src="imageProcessing/gray.png" width=300 alt="Grayscale Image" >
    <img src="imageProcessing/segmented.png" width=300 alt="Segmeneted Image" >
    <img src="imageProcessing/final.png" width=280 alt="Final Cropped Image" >
</div>
<p style="text-align: centre;"> (a) Original Image (b) Instance Segmentation of Original Image (c) Grayscale image of Instance segmentation image (d) Foreground Segmented Image (e) Final Cropped Image</p>

### Foreground Segmentation using Hsv color conversion
<div style="text-align: center;">
    <img src="imageProcessing/original.png" width=300 alt="original Image" >
    <img src="imageProcessing/hsv.png" width=300 alt="Insance Image" >
    <img src="imageProcessing/mask.png" width=300 alt="Grayscale Image" >
    <img src="imageProcessing/final_image.png" width=300 alt="Segmeneted Image" >
</div>
<p style="text-align: centre;"> (a) Original Image (b)Image converted to HSV color scale from RBG (c) Extract plant mask based on color range  (d) Bitwise multiply original image and plant mask</p>

# Model Architecture 
## Generator and Discriminator Architecture
<div style="text-align: center;">
    <img src="imageProcessing/GAN_architecture.png" width=500 alt="GAN architecture" >
</div>

## Loss graph 
### Generator and Discriminator losses during trainig
<div style="text-align: center;">
    <img src="imageProcessing/lossGraph.png" width=500 alt="Loss Graph" >
</div>

# Generated Images
### Generated Images for 1536 X 1536 dimension
<div style="text-align: center;">
    <img src="imageProcessing/1536_1.png" width=300 alt="1536 Image" >
    <img src="imageProcessing/1536_2.png" width=300 alt="1536 Image" >
</div>

### Generated Images for 1024 X 1024 dimension
<div style="text-align: center;">
    <img src="imageProcessing/1024_1.png" width=280 alt="1024 Image" >
    <img src="imageProcessing/1024_2.png" width=280 alt="1024 Image" >
</div>

### Generated Images for 256 X 256 dimension
<div style="text-align: center;">
    <img src="imageProcessing/256_1.png" width=140 alt="256 Image" >
    <img src="imageProcessing/256_2.png" width=140 alt="256 Image" >
</div>

### Generated Images for 64 X 64 dimension
<div style="text-align: center;">
    <img src="imageProcessing/64_1.png" width=100 alt="64 Image" >
    <img src="imageProcessing/64_2.png" width=100 alt="64 Image" >
</div>

## Required Libraries
- python 3.9.7
- torch 1.10.2
- torchvision 0.11.3
- matplotlib 3.5.0
- opencv-python 4.5.5.62

## Host Machine Specifications
- Ubuntu 20.04.1 LTS
- Processor : AMD Ryzen 9 5950x 16-core processor X 32
- RAM memory : 62.7 GB
- GPU memory : 12 GB

## Author 
> Jayanth Somashekaraiah \
> Universität Bremen, Bremen\
> Email: jayanth@uni-bremen.de 
