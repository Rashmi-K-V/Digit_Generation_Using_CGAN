# Digit Generation Using Conditional GAN (CGAN)

## Overview
This project implements a **Conditional Generative Adversarial Network (CGAN)** to generate handwritten digit images conditioned on class labels (0–9). By incorporating label information into both the generator and discriminator, the model can generate specific digits on demand rather than producing random outputs.

The model is trained on the **MNIST dataset** and demonstrates controlled image generation using adversarial learning.

---

## Objectives
- Implement a Conditional GAN from scratch
- Understand adversarial training between generator and discriminator
- Generate digit images conditioned on labels
- Gain hands-on experience with generative deep learning models

---

## Key Concepts
- Generative Adversarial Networks (GAN)
- Conditional GAN (CGAN)
- Deep Learning
- Image Generation
- Adversarial Training
- MNIST Dataset

---

## Tech Stack
- **Programming Language:** Python  
- **Frameworks/Libraries:** TensorFlow, Keras, NumPy, Matplotlib  
- **Environment:** Google Colab / Jupyter Notebook  

---


---

## How It Works
### Generator
- Accepts random noise and a digit label as input
- Generates an image corresponding to the given label

### Discriminator
- Accepts an image and a label as input
- Classifies whether the image is real or generated

### Training Process
- Generator attempts to fool the discriminator
- Discriminator learns to distinguish real images from generated ones
- Both models improve through adversarial training

---


