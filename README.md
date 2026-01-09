# Breast-Cancer-Classification-Project
Breast Cancer Classification using Deep Learning (CancerNet)
🏥 Project Overview
This project implements CancerNet, a Deep Learning architecture designed to detect Invasive Ductal Carcinoma (IDC) in breast histology images. The model utilizes Separable Convolutional layers to achieve high accuracy while remaining computationally efficient.

Key Technical Features
Custom Architecture: Implemented a Sequential CNN featuring SeparableConv2D layers, BatchNormalization, and Dropout for regularization.

Data Pipeline: Automated dataset splitting into training (80%), validation (10%), and testing sets.

Data Augmentation: Enhanced model generalization using real-time image augmentation, including rotations, zooms, and horizontal/vertical flips.

Imbalance Handling: Utilized class weighting to account for the natural imbalance in medical datasets.

🛠️ Tech Stack
Deep Learning: Keras, TensorFlow

Computer Vision: OpenCV, Imutils

Data Science: Scikit-learn, NumPy, Matplotlib

Language: Python

📊 Model Performance
The training script automatically generates performance metrics and a training history plot (plot.png). Key metrics evaluated include:

Accuracy

Sensitivity (Recall)

Specificity

Confusion Matrix

🚀 Getting Started
Install Dependencies: pip install -r requirements.txt

Build Dataset: Place original images in datasets/original and run: python build_dataset.py

Train the Model: python train_model.py
