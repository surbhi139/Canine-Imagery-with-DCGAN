# Canine-Imagery-with-DCGAN

This repository demonstrates the use of Deep Convolutional Generative Adversarial Networks (DCGAN) to generate realistic dog images. The DCGAN model leverages both convolutional layers and adversarial training to create high-quality images that mimic real-world dog photographs.

Project Overview

This project focuses on generating dog images using a DCGAN model. DCGANs are an extension of GANs that specifically utilize convolutional and transposed convolutional layers to improve image quality during training. The dataset consists of images of dogs, and the model learns to generate new, realistic-looking dog images.

Key Features

Data Preprocessing: The dog image dataset is preprocessed to normalize and resize the images for optimal model training.
DCGAN Architecture: The project implements a DCGAN model using convolutional neural networks (CNNs) for the discriminator and transposed convolutional networks for the generator.
Training Process: The model is trained using adversarial training, where the generator and discriminator compete in a game to improve the quality of generated images.
Image Generation: After training, the generator is capable of creating new, realistic dog images that resemble the dataset.

Prerequisites

Python 3.x
TensorFlow or PyTorch (depending on your choice of framework)
NumPy
Matplotlib
OpenCV
