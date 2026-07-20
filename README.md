# Deep Learning-based Visual Similarity Modeling System

## Project Overview

This project presents a PyTorch-based framework for image similarity learning and visual representation analysis.

Three different deep learning approaches were implemented and compared:

- **Triplet Network** for metric learning
- **Variational Autoencoder (VAE)** for unsupervised feature learning
- **Transfer Learning** using pretrained models (VGG16, ResNet-50, ConvNeXt, and Vision Transformer)

The learned feature embeddings were evaluated using cosine similarity to compare the performance of different representation learning strategies on an odd-one-out visual similarity task.

---

## Project Workflow

![Project Workflow](images/workflow.png)

---

## Key Features

- Implemented three representative deep learning approaches for visual similarity learning.
- Built an end-to-end PyTorch training and evaluation pipeline.
- Compared metric learning, unsupervised learning, and transfer learning under the same task.
- Extracted feature embeddings and evaluated image similarity using cosine similarity.
- Compared multiple pretrained architectures including VGG16, ResNet-50, ConvNeXt, and Vision Transformer.

