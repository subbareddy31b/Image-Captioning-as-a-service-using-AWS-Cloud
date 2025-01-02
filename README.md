# Image Captioning as a Service with Multiple Architectures

## Overview
This repository contains an implementation of an **Image Captioning System** using five different deep learning architectures. The models generate descriptive captions for images using the **Flickr8k dataset**. The goal is to compare the performance of different architectures and evaluate the impact of attention mechanisms.

---

## Models
### 1. **EfficientNetB0**
- 📷 A lightweight and efficient architecture for image feature extraction.
- 📷 Known for its balance between accuracy and computational cost.

### 2. **InceptionV3**
- 🌟 Incorporates factorized convolutions and efficient grid size reductions.
- 🌟 Suitable for capturing detailed image features.

### 3. **ResNet**
- 🔄 Implements residual learning to solve the vanishing gradient problem.
- 🔄 Ideal for deep networks with improved feature extraction.

### 4. **VGG16**
- 🏗️ A deep convolutional neural network with 16 layers.
- 🏗️ Focused on simplicity and uniform architecture.

### 5. **VGG16 with Attention Mechanism**
- 🎯 Combines VGG16 with an attention mechanism to improve captioning performance.
- 🎯 Focuses on relevant regions of the image during caption generation.

---

## Dataset
### **Flickr8k Dataset**
- 📂 Contains 8,000 images, each paired with 5 captions.
- 🔗 Dataset Link: [Flickr8k Dataset](https://www.kaggle.com/adityajn105/flickr8k)

---
## Predictions
![Screenshot 2025-01-02 184438](https://github.com/user-attachments/assets/444fea6a-a7d8-4cb9-a510-b04d59e962cd)
![Screenshot 2025-01-02 184417](https://github.com/user-attachments/assets/589e8b2d-3c04-45be-b110-42d3d8747af2)

## Results
| Model                      | BLEU Score |
|----------------------------|----------|
| EfficientNetB0             | 0.48     |
| InceptionV3                | 0.52     |
| ResNet                     | 0.58     |
| VGG16                      | 0.54     |
| VGG16 with Attention       | 0.58     |
---
![download](https://github.com/user-attachments/assets/e25e4257-86e0-4948-b21c-85a7a3f6a128)

## Key Features
🔍 Comparison of five architectures for image captioning.
🎨 Implementation of attention mechanism to enhance caption generation.
💾 Pretrained models for efficient training and evaluation.
🌍 Cloud Deployment for scalable, near real-time predictions.

## Technologies Used
🐍 Python
🧠 TensorFlow/Keras
📊 NumPy, Pandas
📈 Matplotlib for visualization

## Future Enhancements
🗂️ Extend support to other datasets (e.g., COCO dataset).
🤖 Add additional transformer-based models like ViT or BERT for Vision.
