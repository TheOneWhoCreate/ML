# Autoencoder Feature Learning

This project implements an undercomplete Autoencoder using TensorFlow/Keras for feature learning and dimensionality reduction.  
The model learns compressed feature representations (latent vectors) and evaluates their effectiveness for classification tasks.

---

# What's Covered

## Autoencoder Architecture
- Encoder network
- Bottleneck (latent space)
- Decoder network
- Feature compression

## Data Preprocessing
- Dataset normalization
- Train-Test split
- Feature scaling using MinMaxScaler

## Feature Learning
- Learning compressed latent representations
- Reconstruction of original input data
- Dimensionality reduction using Autoencoders

## Model Training
- Mean Squared Error (MSE) loss
- Adam optimizer
- Early stopping

## Classification Comparison
- Logistic Regression on:
  - Raw input data
  - Compressed latent features

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Reconstruction Error

---

# Visualization

- Reconstruction Error Distribution
- Original vs Reconstructed Images
- t-SNE Visualization of Latent Space
- Autoencoder Training Curves

---

# What You Will Learn

- How Autoencoders learn compressed representations
- Difference between raw and latent features
- Importance of bottleneck layers
- How reconstruction works in Autoencoders
- How feature compression affects classification performance
- Visualization of learned latent feature space
- Applications of dimensionality reduction in Deep Learning