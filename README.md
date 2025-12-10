# Comparative-Study-of-CNNs-and-Transfer-Learning-Using-ResNet50-for-Image-Classification
7PAM2021-0901-2025: Individual Assignment: Machine Learning Tutorial

Author: Sri Lekha Thorlapati
Student ID: 24091865

Dataset
Intel Image Classification (Kaggle): https://www.kaggle.com/datasets/puneet6060/intel-image-classification

Project Overview

This repository presents a tutorial-style comparative study between:
  -A custom-built Convolutional Neural Network (CNN) trained from scratch
  -A ResNet50 transfer learning model pretrained on ImageNet

The objective is to demonstrate why pretrained deep networks significantly outperform models trained from scratch—especially when the available dataset is limited.

The notebook includes:
✅ Architecture design
✅ Training curves
✅ Confusion matrices
✅ Classification reports
✅ Prediction examples
✅ Final model comparison

Models Implemented
1. Baseline CNN (Trained from Scratch)
-3 convolution blocks
-11 million parameters
-Early overfitting
-Validation accuracy: 79%
-Confusion between glacier and mountain
-Poor generalisation

2. ResNet50 Transfer Learning
-Pretrained on ImageNet
-Frozen convolution layers
-Custom classification head
-Validation accuracy: 91.8%
-Dramatic accuracy improvement
-Excellent generalisation

How to Run

--Download dataset from Kaggle

--Extract into project directory

--Open notebook

--Run all cells

--Models train automatically

--Visuals generated

--Metrics evaluated
