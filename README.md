# AutoEncoders
Day 1: Implemented ANN-based autoencoder for MNIST using TensorFlow to understand latent representations
# Grayscale Image Autoencoder (ANN)

##  Overview
This project implements a **basic Autoencoder using Artificial Neural Networks (ANN)**
to learn compressed representations of **grayscale images**.
The model is trained on the **MNIST dataset** and learns to reconstruct the input images.

This project is built to understand the **fundamental concept of autoencoders**
before moving to CNN-based and Variational Autoencoders.

---

## Main Concept
An autoencoder is an **unsupervised learning model** where:
- Input image = Output image
- The network learns a **latent (compressed) representation**
- Training minimizes **reconstruction error**

---

## Dataset
- **MNIST**
- 28 × 28 grayscale handwritten digit images
- Images are normalized to the range **[0, 1]**

---

##  Model Architecture (ANN)

