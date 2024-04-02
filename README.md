# Satellite-images-to-cartoon-type-images-using-GAN

### Satellite Image to Google Maps Image Conversion using GANs

This project entails an attempt to implement a Generative Adversarial Network (GAN) architecture for transforming satellite images into images resembling those found in Google Maps. The project was developed and trained within a Kaggle Jupyter notebook environment.

#### About the Project

The primary objective of this project is to explore the capabilities of GANs in the domain of image-to-image translation, specifically focusing on converting satellite images into the style reminiscent of Google Maps imagery. The architecture employed in this project consists of a U-Net generator coupled with a PatchGAN discriminator.

[Kaggle Notebook Link](https://www.kaggle.com/code/dobariyanaitik/pix2pix-gan-to-generate-maps-from-satellite-images)

The U-Net generator is designed to capture high-level features while preserving spatial information, facilitating the transformation of satellite images into the characteristic style of Google Maps imagery. Concurrently, the PatchGAN discriminator evaluates the local image patches, enabling fine-grained discrimination between real and generated images.

#### Libraries Used

- matplotlib
- numpy
- glob
- tensorflow
- keras

#### Results

The GAN model underwent training for 100 epochs, resulting in satisfactory outcomes. Below are samples showcasing the transformation of satellite images into Google Maps-style images:

![__results___18_1](https://github.com/NaitikDobariya/Satellite-images-to-cartoon-type-images-using-GAN/assets/113834773/445f4306-864c-4748-b0e8-1992bd64a6f7)

![__results___18_3](https://github.com/NaitikDobariya/Satellite-images-to-cartoon-type-images-using-GAN/assets/113834773/5cadbca3-4caa-4c97-ab1d-7f5f44f96d38)

![__results___18_5](https://github.com/NaitikDobariya/Satellite-images-to-cartoon-type-images-using-GAN/assets/113834773/d0eb42f0-329d-4498-80e7-5354cef074e0)

![__results___18_7](https://github.com/NaitikDobariya/Satellite-images-to-cartoon-type-images-using-GAN/assets/113834773/0c0619bf-0c3a-4fb6-b249-8945528991b6)


The results are not perfect and there is a huge scope for improvement, changes in the architecture and hyperparameters might lead to better results.Suggestions and changes are most welcome.
