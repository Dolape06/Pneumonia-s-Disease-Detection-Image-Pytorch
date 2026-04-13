# 🫁 Pneumonia Detection from Chest X-Rays with Deep Learning

## 📌 Overview

This project builds an end-to-end **computer vision classification system** capable of detecting **pneumonia from chest X-ray images** using a custom Convolutional Neural Network (CNN).

The model learns visual patterns such as lung opacity, texture irregularities, and structural changes to accurately distinguish between **NORMAL** and **PNEUMONIA** cases.

Designed as a full deep learning pipeline, the system covers data loading, preprocessing, model training, evaluation, visualization, and real-world predictions on unseen images.

---

## 🗂 Dataset

The model is trained on the **Chest X-Ray Pneumonia dataset**, a medical image dataset available on **Kaggle**.

### Dataset Characteristics

• 2 classes: NORMAL and PNEUMONIA 
• Thousands of labeled chest X-ray images 
• Real medical imaging data 
• Pre-split into training and testing sets 
• Ideal for binary image classification tasks 

### 📥 Download Dataset

You can download the dataset here:
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

After downloading, extract the folders into your project directory:

```
train/
test/
val/
```

---

## 🌍 Real-World Problems This Model Solves

Automated medical image analysis is essential in environments where fast and accurate diagnosis supports healthcare professionals.

This system helps solve:

### • Clinical Decision Support

Assists doctors in identifying pneumonia from chest X-rays quickly.

### • Faster Diagnosis

Reduces time required for manual interpretation of medical images.

### • Healthcare Accessibility

Provides AI assistance in regions with limited access to radiologists.

### • Medical AI Automation

Supports automated diagnostic systems in hospitals and clinics.

### • Assistive AI Systems

Helps medical staff analyze and interpret imaging data efficiently.

---

## ⭐ Why This Is Important

Manual analysis of X-ray images is:

• Slow
• Costly
• Error-prone
• Difficult to scale

Computer vision automation enables:

• Faster diagnosis
• Reduced workload for radiologists
• High consistency
• Scalable healthcare systems
• Improved medical workflows

Medical image classification is a foundational technology in modern AI-assisted healthcare.

---

## ⚙️ Technical Approach

### 1️⃣ Image Preprocessing

• Image resizing to uniform dimensions

• Pixel normalization

• RGB conversion

• Structured dataset loading using PyTorch DataLoader

### 2️⃣ Label Encoding

• Class labels converted to numeric values

• Binary classification setup

### 3️⃣ CNN Architecture

The custom CNN consists of:

• Multiple Convolutional layers for feature extraction

• Activation functions (ReLU)

• MaxPooling for spatial reduction

• Fully connected layers for classification

• Output layer for binary prediction

### 4️⃣ Training Strategy

• Optimizer: Adam

• Loss Function: CrossEntropyLoss

• Mini-batch training

• Multiple epochs

### 5️⃣ Evaluation & Visualization

• Confusion Matrix

• Classification Report

• Accuracy evaluation

### 6️⃣ Real-World Prediction

• Model saved and reloaded for inference

• Predicts unseen chest X-ray images

• Displays predicted label with confidence score

---

## 📊 Model Performance

• Test Accuracy: **79%**

• Strong detection of pneumonia cases with high confidence

• Successfully classified new unseen chest X-ray images with more than 96% confidence for each image 

The model demonstrates reliable performance for pneumonia detection tasks.

---

## 🚀 Applications

✔ Medical Diagnosis Assistance 
✔ AI-powered Radiology Systems 
✔ Healthcare Automation 
✔ Clinical Decision Support 
✔ Computer Vision Research 

---

## 🧠 Possible Extensions

• Transfer learning with ResNet or EfficientNet 
• Improve class balance handling 
• Real-time medical image analysis 
• Deploy as web application using streamlit
• Add explainability tools (Grad-CAM) 
• Integration into healthcare systems

---

## 🛠 Tech Stack

Python • PyTorch • NumPy • Matplotlib • Scikit-learn

---
