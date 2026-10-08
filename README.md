# Neural Networks — Coursework and Final Project

Coursework and a final project from **Redes Neuronales** at FaMAF, Universidad Nacional de Córdoba. The course was completed in **February 2024**.

The main project implements a convolutional autoencoder in **PyTorch** and reuses its encoder in a classifier for **Fashion-MNIST**.

## Start here

- [Final project notebook](Trabajo%20Integrador/trabajo_integrador_Angaut.ipynb)
- [Written report (PDF)](Trabajo%20Integrador/Trabajo_Integrador_ANGAUT.pdf)
- [Open the final notebook in Google Colab](https://colab.research.google.com/github/gonzaloangaut/NeuralNetworks/blob/main/Trabajo%20Integrador/trabajo_integrador_Angaut.ipynb)

The notebooks and report retain the original Spanish explanations.

## Final project: reconstruction and classification

The project connects unsupervised representation learning with supervised image classification:

1. Train a convolutional autoencoder to reconstruct Fashion-MNIST images.
2. Copy the trained encoder into a classifier with a ten-class output.
3. Train the classifier, including the encoder parameters, with cross-entropy loss.
4. Inspect reconstruction examples, learning curves, classification accuracy, and a confusion matrix.

The implementation includes convolutional and transposed-convolutional layers, a 64-dimensional latent representation, dropout, Adam optimization, and explicit training and evaluation loops.

This is a completed educational project. The original notebook uses Fashion-MNIST's official test split as validation data during training, so its displayed validation results should be read in that context.

## Practicals

The [Practicos](Practicos/) folder contains the course exercises, covering:

- numerical computing with NumPy and SciPy;
- linear algebra, ODE integration, and dynamical systems;
- Integrate-and-Fire, Hodgkin–Huxley, and Izhikevich neuron models;
- single-layer networks and multilayer perceptrons;
- PyTorch tensors, image classification, and autoencoders.

## Running the notebook

The final notebook was developed in Google Colab and includes Colab-specific imports. Open it with the link above and run the cells in order; Fashion-MNIST is downloaded by the notebook.

The saved outputs come from the original coursework. Dependencies are installed in the notebook and are not pinned to a reproducible environment.

## Author

Gonzalo Angaut
