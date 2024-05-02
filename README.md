# Anomly_detection

o build an anomaly detection framework that integrates contrastive learning and GAN to address overfitting in multivariate time series data, we'll follow these steps:

1- Data Augmentation with Geometric Distribution Masks:
Implement the data augmentation technique with geometric distribution masks to generate augmented samples of the original multivariate time series data. In result a matrix will be acheived that will be a binary noise matrix. 

2- Transformer-based Autoencoder:
Implement a Transformer-based autoencoder architecture. This autoencoder will consist of an encoder and a decoder, where the encoder maps the input multivariate time series data into a latent representation and the decoder reconstructs the original data from this latent representation.

3- Contrastive Learning:
Defining a contrastive loss function that encourages similar representations for similar data points and dissimilar representations for dissimilar data points.

4- GAN Framework:
Integrate the autoencoder into a GAN framework.

5- Training:
Train the GAN. 

6- Anomaly Detection:
After training, anomaly detection can be performed by using the reconstruction error between the original and reconstructed data. Instances with high reconstruction error can be flagged as anomalies.
