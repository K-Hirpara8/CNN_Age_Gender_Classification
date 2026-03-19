# 👩‍💻 CNN-Based Gender and Age Classification

## 📌 Overview

This project focuses on gender and age-group classification using Convolutional Neural Networks (CNNs). The model is trained on labeled facial image datasets and evaluated on validation data to analyze classification performance.

The goal of this project was to gain hands-on experience in supervised deep learning for image-based prediction tasks and understand how preprocessing and architectural choices influence model performance.

---

## 🧠 Model Approach

- Facial images are resized and normalized before training.
- The dataset is divided into training and validation sets.
- CNN models are implemented using TensorFlow / Keras.
- Performance is evaluated using standard classification metrics.
- The trained model is used to generate predictions on individual input images.

---

## ⚙️ Implementation Details

- Image preprocessing (resizing, normalization)
- Dataset splitting (training / validation)
- CNN architecture design and training
- Model evaluation
- Inference pipeline for single images

The project emphasizes understanding the full workflow — from raw image data to final predictions.

---

## 📊 Results & Observations

- The model successfully learned distinguishable facial features for gender classification.
- Age-group prediction performance depended on class balance and dataset quality.
- Model accuracy improved after adjusting architecture depth and training epochs.
- Proper normalization and consistent image resizing significantly stabilized training.

The experiments helped me understand how model structure and preprocessing choices directly impact learning behavior.

---

## 🖼 Example Inference

After training, the model can:

- Take a single facial image as input
- Preprocess it consistently
- Predict gender category
- Predict age group category

This demonstrates how a trained CNN can be integrated into a simple inference pipeline.

---

## 📂 Project Structure

    ├── Age & Gender Final.ipynb
    ├── README.md
    ├── requirements.txt

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib

---

## 📥 Installation

Install required libraries:

    pip install -r requirements.txt

---

## ▶️ Running the Project

Open the notebook:

    Age & Gender Final.ipynb

Run all cells sequentially to:

- Load and preprocess the dataset
- Train the CNN model
- Evaluate validation performance
- Generate predictions

---

## 🎯 What I Learned

- Designing CNN architectures for image classification
- Importance of image preprocessing and normalization
- Evaluating deep learning models properly
- Understanding how architecture depth influences accuracy
- Building a basic inference pipeline for trained models
