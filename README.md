# 🧬 Breast Cancer Classification (CancerNet)

![Deep Learning](https://img.shields.io/badge/Framework-Keras%20%2F%20TensorFlow-critical?style=flat-square)
![Computer Vision](https://img.shields.io/badge/Domain-Computer%20Vision-blue?style=flat-square)
![Medical AI](https://img.shields.io/badge/Focus-Medical%20Diagnostics-success?style=flat-square)

## 🏥 Project Overview
This project implements **CancerNet**, a deep learning architecture specifically designed to detect **Invasive Ductal Carcinoma (IDC)** in breast histology images. The model utilizes **Separable Convolutional layers** to achieve high classification accuracy while remaining computationally efficient for medical environments.

---

## 🛠️ Tech Stack
* **Deep Learning:** Keras, TensorFlow
* **Computer Vision:** OpenCV, Imutils
* **Data Science:** Scikit-learn, NumPy, Matplotlib
* **Language:** Python

---

## 🧪 Key Technical Features

### 🏗️ Custom Architecture (CancerNet)
* **Sequential CNN:** Implemented using `SeparableConv2D` layers for efficient spatial feature extraction.
* **Regularization:** Integrated `BatchNormalization` and `Dropout` (0.25 to 0.5) to ensure model stability and prevent overfitting.
* **Activation:** Utilizes ReLU for hidden layers and Softmax for final classification.

### 📉 Data Engineering Pipeline
* **Automated Dataset Building:** Scripts to split raw data into Training (80%), Validation (10%), and Testing (10%) sets.
* **Real-time Augmentation:** Enhanced model generalization using `ImageDataGenerator` for rotations, zooms, and horizontal/vertical flips.
* **Imbalance Handling:** Utilizes class weighting to account for the natural class imbalance in medical IDC datasets.

---

## 📊 Model Performance
The training script generates comprehensive performance metrics and a history plot (`plot.png`). Key metrics evaluated include:
* **Accuracy:** Overall classification correctness.
* **Sensitivity (Recall):** Ability to correctly identify positive IDC cases.
* **Specificity:** Ability to correctly identify negative cases.
* **Confusion Matrix:** Detailed breakdown of true vs. false predictions.

---

