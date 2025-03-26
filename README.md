# My_projects
# Project Title : Neural Style Transfer using VGG19
# Overview
This project implements Neural Style Transfer (NST) using the VGG19 model. NST is a deep learning technique that blends the content of one image with the artistic style of another, creating a visually stylized output.

# How It Works
1) Uses VGG19, a pre-trained convolutional neural network, to extract features.

2) Extracts content features from deeper layers to retain image structure.

3) Captures style features using Gram matrices from multiple layers.

4) Optimizes a loss function combining content and style loss to generate the final stylized image.
