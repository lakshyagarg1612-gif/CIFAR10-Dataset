
***

# 📘 Beginner Assignment: ANN and CNN on CIFAR-10 Dataset

## 🎯 Objective

This assignment focuses on implementing and comparing **Artificial Neural Networks (ANN)** and **Convolutional Neural Networks (CNN)** for image classification using the CIFAR-10 dataset.

***

## 📊 Dataset: CIFAR-10

* Contains **60,000 color images**
* Divided into:
  * 50,000 training images
  * 10,000 testing images
* Each image has a size of **32 × 32 pixels with 3 color channels (RGB)**
* Includes **10 different classes**

### 🏷️ Classes

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

***

## 🎓 Learning Outcomes

* Understand how to load datasets directly from TensorFlow/Keras
* Learn the conceptual difference between ANN and CNN
* Build simple ANN and CNN architectures for image classification
* Train, test, and evaluate machine learning models
* Analyze and compare model performance

***

## ⚙️ General Instructions

* Use **Python with TensorFlow/Keras**
* Load the dataset directly from Keras (no manual download required)
* Apply basic preprocessing by **normalizing pixel values (0–255 → 0–1)**
* Train ANN and CNN models separately
* Evaluate models using **accuracy and loss**
* Write a comparison based on model performance

***

## 📥 Dataset Understanding

* Training data consists of **50,000 images**
* Testing data consists of **10,000 images**
* Each image is represented as a **32 × 32 × 3 array**
* Labels are integer values from **0 to 9**, corresponding to class categories

***

## 🔄 Data Preprocessing

Before training:

* Pixel values must be scaled from **0–255 to 0–1**
* This helps neural networks converge faster and perform better

***

# 🧠 Project 1: ANN on CIFAR-10

### 📌 Problem Statement

Build a basic Artificial Neural Network to classify images into 10 categories and observe its limitations for image data.

***

## ✅ Tasks Overview

* Import necessary libraries
* Load the dataset
* Understand dataset structure and shape
* Normalize pixel values
* Build a simple ANN model
* Compile the model
* Train the model
* Evaluate performance on test data
* Make predictions and compare with actual labels
* Write observations

***

## 🏗️ ANN Architecture (Concept)

* Images are flattened into a **1D vector**
* Fully connected (dense) layers are used
* Final layer outputs probabilities for 10 classes

***

## 📝 Observation (ANN)

* Provides **moderate accuracy**
* Does not preserve spatial structure of images
* Struggles to learn important visual patterns like edges and textures
* Not ideal for image classification tasks

***

# 🧠 Project 2: CNN on CIFAR-10

### 📌 Problem Statement

Build a Convolutional Neural Network to better handle image data using convolution and pooling techniques.

***

## ✅ Tasks Overview

* Use convolution layers for feature extraction
* Apply pooling layers to reduce dimensionality
* Flatten features before classification
* Train and evaluate the model
* Compare results with ANN

***

## 🏗️ CNN Architecture (Concept)

* Convolution layers detect features such as edges and shapes
* Pooling layers reduce image size and computation
* Fully connected layers perform classification

***

## 📝 Observation (CNN)

* Achieves **higher accuracy compared to ANN**
* Preserves spatial relationships in images
* Automatically learns important features
* More suitable for image classification tasks

***

# ⚖️ ANN vs CNN Comparison

| Feature           | ANN             | CNN                          |
| ----------------- | --------------- | ---------------------------- |
| Input Handling    | Flattened (1D)  | Maintains 2D structure       |
| Feature Learning  | Limited         | Automatic feature extraction |
| Accuracy          | Low to Moderate | Moderate to High             |
| Image Suitability | Poor            | Excellent                    |

***

## ✅ Conclusion

* ANN is simple but not effective for image data
* CNN is designed specifically for images and performs significantly better
* CNN should be preferred for most computer vision tasks

***

✅ **Tip:** This is a beginner-friendly assignment, so keep models simple and focus on understanding concepts rather than optimization.

***

