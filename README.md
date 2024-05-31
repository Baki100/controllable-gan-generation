# 🌀 Controllable Generation with GANs

This project focuses on implementing a GAN controllability method using gradients from a classifier. By training a classifier to recognize a relevant feature, we can use it to adjust the generator's inputs (z-vectors) to produce images with varying degrees of that feature.

## Learning Objectives

📚 **1. Observe how controllability can change a generator's output.**

📚 **2. Resolve some of the challenges that entangled features pose to controllability.**

## Getting Started

**1. Import Libraries**: Import necessary libraries and packages.

**2. Define Visualization**: Create a function to visualize the generated images.

**3. Utilize Pre-trained Models**: Use the provided pre-trained generator and classifier for controllability tasks.

## Dataset

🖼 For this notebook, we will use the [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) dataset. CelebA is a dataset of annotated celebrity images, which are colored with three channels: red, green, and blue (RGB).
