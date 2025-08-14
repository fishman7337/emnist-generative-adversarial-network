# Generative Adversarial Network (GAN)

## Project Overview
This project implements a **Generative Adversarial Network (GAN)** to generate synthetic handwritten digit images using the **MNIST dataset**. The focus is on understanding the adversarial training process, model stability, and qualitative evaluation of generated outputs.

## Features
- **Data Loading & Preprocessing**
  - MNIST dataset (28×28 grayscale images)
  - Pixel normalisation to range [-1, 1]
- **GAN Architecture**
  - **Generator**: Fully connected layers with LeakyReLU activations and batch normalisation
  - **Discriminator**: Fully connected layers with LeakyReLU activations and sigmoid output
- **Training Process**
  - Adversarial training loop for generator and discriminator
  - Loss monitoring for both networks
- **Evaluation**
  - Generated image grid visualisations at intervals
  - Qualitative analysis of output fidelity

## Key Insights
- The GAN successfully learns to generate realistic MNIST digits after sufficient training epochs.
- Output quality improves over time, with sharper digit shapes and reduced noise.
- Early training stages often produce blurry and indistinct samples.

## Tech Stack
- **Python** (TensorFlow/Keras, NumPy, Matplotlib)
- **Jupyter Notebook** for experimentation
