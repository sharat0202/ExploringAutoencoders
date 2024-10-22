# Exploring Autoencoders: Variants and Applications

This project explores the use of PCA and various autoencoder architectures for dimensionality reduction, classification, and reconstruction error analysis using image data.

### Tasks Overview

#### Task 1: PCA and Logistic Regression

    Perform Standard PCA to reduce the dimensionality, identifying eigenvectors with ≥95% total energy.
    Train a Logistic Regression classifier using the reduced features to classify images into 10 classes.
    Draw the ROC Curve for the test dataset.
    Repeat the process using Randomized PCA and compare the results with Standard PCA.

#### Task 2: Single Layer Autoencoder vs. PCA

    Train a Single Layer Autoencoder with a linear activation function.
    Compare the eigenvectors obtained from PCA with those from the autoencoder.
    Analyze and explain the similarities/differences in eigenvector representations.

#### Task 3: Deep Convolutional Autoencoder

    Train a Deep Convolutional Autoencoder with the same latent space dimension as Task 2.
    Compute and compare the reconstruction error with the single hidden layer autoencoder (using sigmoid activation at the encoder and linear activation at the decoder).
    Train a 3-hidden layer autoencoder with approximately equal hidden nodes, using sigmoid activation at the encoder and linear activation at the decoder. Analyze the reconstruction error.

### Key Comparisons

    PCA vs. Autoencoders: Eigenvector analysis and classification performance.
    Single Layer vs. Deep Autoencoders: Reconstruction error across different autoencoder architectures.

This project demonstrates the effectiveness of PCA and various autoencoder models in dimensionality reduction and image classification tasks.