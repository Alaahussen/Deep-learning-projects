# Deep Learning Projects Overview

This repository contains multiple deep learning projects developed for computer vision tasks using **Artificial Neural Networks (ANNs)**, **Convolutional Neural Networks (CNNs)**, and **pretrained models**. The projects focus on **image classification** and **image segmentation** using various datasets and architectures.

---

## 🔍 Project Structure

- `projects/ann/` – Image classification using basic Artificial Neural Networks.
- `projects/cnn/` – Image classification using custom-built CNN architectures.
- `projects/pretrained/` – Transfer learning using pretrained models like VGG, ResNet, and EfficientNet.
- `projects/segmentation/` – Semantic and instance segmentation tasks using U-Net and other architectures.

---

## 🧠 Techniques Used

### 1. Artificial Neural Networks (ANN)
- Implemented basic fully-connected networks for image classification.
- Used for small grayscale datasets like MNIST and Fashion-MNIST.
- Training involved backpropagation with optimizers like SGD and Adam.

### 2. Convolutional Neural Networks (CNN)
- Built custom CNNs from scratch using layers like Conv2D, MaxPooling, and Dropout.
- Applied to datasets such as CIFAR-10 and medical imaging datasets.
- Demonstrated superior performance over ANNs for image-based tasks.

### 3. Pretrained Models (Transfer Learning)
- Used models pretrained on ImageNet for feature extraction and fine-tuning.
- Models: `ResNet50`, `VGG16`, `InceptionV3`, `EfficientNetB0`, etc.
- Fine-tuned final layers for custom classification datasets.

### 4. Image Classification
- Tasks include classifying objects, animals, diseases, and skin conditions.
- Evaluation metrics: Accuracy, Precision, Recall, F1-score.
- Data augmentation used to improve generalization.

### 5. Image Segmentation
- Used U-Net, FCN, and DeepLab models for pixel-wise prediction.
- Tasks: Tumor segmentation, organ boundary detection, road segmentation.
- Evaluation metrics: IoU (Intersection over Union), Dice coefficient.
