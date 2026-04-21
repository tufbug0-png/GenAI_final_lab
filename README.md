#  Denoising Autoencoder (DAE) on Fashion-MNIST

This project implements a **Denoising Autoencoder (DAE)** using PyTorch to learn robust feature representations from the Fashion-MNIST dataset. The model reconstructs clean images from noisy inputs.

---

## Project Overview

A **Denoising Autoencoder**:
- Takes a noisy image as input
- Encodes it into a latent representation
- Decodes it back to reconstruct the clean image

### Applications:
- Noise removal
- Feature extraction
- Dimensionality reduction

---

## Dataset

- Dataset: Fashion-MNIST
- Image Size: 28 × 28 (grayscale)
- Total Features: 784 pixels
- Format: CSV

---

## Requirements

Install dependencies:

```bash
pip install torch pandas matplotlib
