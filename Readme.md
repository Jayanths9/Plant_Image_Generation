# Index
## Repository contains source code of master's project titled " Synthetic Generation of Plant Dataset Using GANs"
## DCGAN.ipynb
- DCGAN_Training.ipynb
    - loading dataset into dataloader
    - Generator architecture.
    - Discriminator architecture.
    - Training of DCGAN.
<br></br>
- dataPreprocessing.ipynb
    - Foreground segmentation of original images.
    - Hsv based segmentation of original plant images.
 <br></br>
- generateImages.ipynb
    - script to generate 1462 x 1462 dimension images and resize them to 1536 x 1536
<br></br>
- trainedModels
    - DCGAN model to generate 1462 
<br></br>

## styleGAN3
- trainedModels
    - Style GAN 3 model trained on plant segmentation images of 256 x 256 dimension.
    - Style GAN 3 model trained on plant segmentation images of 512 x 512 dimension.
- Readme.md
    - links to research papers related to Style GAN 3.
    - instructions to setup and train Style GAN 3 on local machine.
    - instructions to generate images for 256 x 256 and 512 x 512 image dimensions from trained Style GAN 3 model.
    - generated images from trained models.

## Author 
> Jayanth Somashekaraiah \
> Universität Bremen, Bremen\
> Email: jayanth@uni-bremen.de 