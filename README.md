# image_Classification

## Description

This project utilizes the CIFAR-10 dataset, which contains 60,000 images commonly used for building image recognition models. Specifically, I focused on the 12,000 images of cars and trucks, with 6,000 images per class. Each pixel in the 32x32 images, represented by three color channels, contributes to over 3,000 features per image. Due to the high dimensionality, I implemented two dimensionality reduction techniques—Non-Negative Matrix Factorization (NMF) and Principal Component Analysis (PCA)—to mitigate overfitting and reduce model runtime. After splitting the data into training, testing, and validation sets, I processed it through a Convolutional Neural Network (CNN).
