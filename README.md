# Neural Networks Course – Practice & Final Project

This repository contains the material developed during a university (FaMAF, UNC) course on neural networks, covering topics from the biological foundations of neurons to modern deep learning architectures.

## Overview

The course provides a comprehensive introduction to neural networks, starting from fundamental concepts such as neuron models and dynamical systems, and progressing towards fully trainable deep learning models.

Throughout the course, both theoretical understanding and practical implementation were emphasized, including the use of **PyTorch** for modern machine learning workflows.

---

## Practicals

The `Practicos/` folder contains a series of hands-on notebooks developed during the course. These exercises progressively build the necessary tools and intuition for understanding neural networks.

Topics include:

* Python and Google Colab basics
* Numerical computing with NumPy and SciPy
* Linear algebra and numerical integration of ODEs
* Dynamical systems (Lorenz system, logistic map)
* Biophysical neuron models:

  * Integrate-and-Fire
  * Hodgkin–Huxley
  * Izhikevich
* Introduction to neural networks:

  * Single-layer networks
  * Multilayer perceptrons
* Deep learning with PyTorch:

  * Tensor operations
  * Model fitting via least squares
  * Image classification (Fashion-MNIST)
  * Autoencoders and convolutional autoencoders

---

## Final Project

The `Trabajo Integrador/` folder contains the final project of the course, including both a Jupyter notebook and a written report.

### Project: Autoencoder + Convolutional Classifier (Fashion-MNIST)

In this project, a **convolutional autoencoder** was implemented and trained to learn compressed representations of images from the Fashion-MNIST dataset. The encoder was then reused to build a **classifier**, leveraging learned features for improved performance.

Key aspects:

* Implementation in **PyTorch**
* Use of convolutional and transposed convolutional layers
* Regularization via dropout
* Training with ADAM optimizer
* Evaluation using:

  * Reconstruction error
  * Classification accuracy (~90%)
  * Confusion matrix

The project demonstrates how unsupervised learning (autoencoders) can be combined with supervised learning to build efficient models for image classification.

---

## Tools & Technologies

* Python
* NumPy / SciPy
* Matplotlib
* **PyTorch**
* Google Colab

---

## Key Takeaways

* Strong foundation in both biological and mathematical models of neurons
* Experience with dynamical systems and numerical simulations
* Practical implementation of neural networks from scratch
* Hands-on experience with modern deep learning frameworks (**PyTorch**)
* End-to-end development of a deep learning project

---

## Author

**Gonzalo Angaut**
