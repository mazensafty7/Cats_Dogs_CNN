# Cats vs. Dogs Image Classifier

![An-example-of-a-Supervised-Learning-classification-of-cats-and-dogs-and-b](https://github.com/user-attachments/assets/37d1d0fb-81a6-4436-b9a9-ff7ea1b63ed0)

This project is a basic image classifier that uses a Convolutional Neural Network (CNN) to distinguish between images of cats and dogs. The model is trained on a labeled dataset and can predict whether a given image contains a cat or a dog.

## Project Overview

The classifier is built using TensorFlow and Keras, leveraging the power of CNNs to automatically detect and learn patterns in images. The model is trained on a dataset of cat and dog images, and the performance is evaluated on a separate test set.

## Key Features

- **CNN Architecture:** Utilizes a Convolutional Neural Network with multiple layers to extract features from images.
- **Binary Classification:** The model outputs a binary prediction, classifying images as either 'Cat' or 'Dog'.
- **Data Preprocessing:** Includes image resizing, normalization, and augmentation to improve model performance.
- **Model Training:** Trained on a dataset of cat and dog images with categorical cross-entropy loss and the Adam optimizer.

## Dataset

The dataset used in this project contains labeled images of cats and dogs. The images are preprocessed to a uniform size of 100x100 pixels and normalized to enhance model training.

## Results

The model achieves a certain accuracy on the test set, and sample predictions are displayed, showcasing the model's ability to classify images of cats and dogs.
