# Sugarcane Leaf Disease Detection using CNN & Transfer Learning

This project focuses on identifying and classifying sugarcane leaf diseases using Convolutional Neural Networks (CNNs) and pre-trained deep learning models via transfer learning. It was developed as part of the EPICS project.

## 📂 Project Structure

- `EPICS_CNN_Model.ipynb`: Custom CNN built from scratch
- `EPICS_DENSE_NET_201.ipynb`: Transfer learning using DenseNet201
- `EPICS_ResNet50.ipynb`: Transfer learning using ResNet50
- `Epics_VGG19.ipynb`: Transfer learning using VGG19

## 📊 Objective

To classify images of sugarcane leaves into distinct disease categories (or healthy) using deep learning techniques. The focus is on comparing the performance of a basic CNN vs. advanced transfer learning models.

## 🔧 Technologies

- Python, TensorFlow / Keras
- OpenCV / PIL for preprocessing
- CNN, ResNet50, DenseNet201, VGG19
- Data Augmentation, Fine-Tuning, Dropout
- Evaluation: Accuracy, Precision, Recall, Confusion Matrix

## 🚀 How It Works

1. Load and preprocess the leaf image dataset (resizing, augmentation, normalization).
2. Train a baseline CNN.
3. Apply transfer learning using multiple pre-trained models.
4. Evaluate and compare results across models.

## ✅ Outcomes

- DenseNet201 and ResNet50 showed the best accuracy and generalization.
- Transfer learning significantly outperformed the custom CNN.
- Final model can be deployed as a diagnostic assistant for sugarcane farmers.

## 🧠 Concepts Covered

- CNN fundamentals and convolutional blocks
- Transfer learning and feature extraction
- Overfitting mitigation via dropout and augmentation
- Performance evaluation with classification metrics

## ✍️ Author

Akshit Soni
