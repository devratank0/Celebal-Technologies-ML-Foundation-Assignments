# 🧠 Denoising Autoencoder using MNIST

This repository contains my **Week 6 Machine Learning Foundation assignment** completed as part of the **Celebal Technologies Internship Program**.

---

## 📌 Project Overview

This project focuses on building a **Convolutional Denoising Autoencoder** using the **MNIST handwritten digit dataset**. The objective is to train a deep learning model capable of reconstructing clean handwritten digit images from noisy inputs. The project demonstrates the application of Autoencoders for image denoising, feature extraction, and image reconstruction.

---

## 🎯 Objectives

- Load and preprocess the MNIST dataset
- Normalize and reshape image data
- Add Gaussian noise to create noisy images
- Build a Convolutional Denoising Autoencoder
- Train the Autoencoder using noisy images as input
- Reconstruct clean images from noisy inputs
- Evaluate model performance using loss curves
- Compare original, noisy, and reconstructed images
- Analyze the effectiveness of the Autoencoder

---

## 🛠️ Tools and Libraries Used

- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Matplotlib

---

## 📂 Repository Structure

```text
Week-6/
│
├── ML_Foundation_Week_6_Denoising_Autoencoder_MNIST.ipynb
└── README.md
```

---

## 📂 Dataset

This project uses the **MNIST Handwritten Digits Dataset**, which is automatically loaded using the TensorFlow/Keras API.

```python
from tensorflow.keras.datasets import mnist
```

No separate dataset download or upload is required.

---

## 🔄 Workflow Followed

1. Import required libraries
2. Load the MNIST dataset
3. Explore the dataset
4. Normalize image pixel values
5. Reshape images for CNN input
6. Add Gaussian noise to images
7. Visualize original and noisy images
8. Build the Convolutional Denoising Autoencoder
9. Compile the model
10. Configure EarlyStopping
11. Train the Autoencoder
12. Plot training and validation loss
13. Generate denoised images
14. Compare original, noisy, and reconstructed images
15. Analyze results and summarize findings

---

## 📈 Results

- Successfully trained a Convolutional Denoising Autoencoder.
- Training and validation loss decreased consistently throughout training.
- The model effectively reconstructed clean handwritten digit images from noisy inputs.
- Visual comparisons demonstrated significant noise reduction while preserving digit features.

---

## 📚 Key Learning Outcomes

This project helped strengthen my understanding of:

- Autoencoders
- Image Denoising
- Encoder-Decoder Architecture
- Convolutional Neural Networks (CNNs)
- Feature Extraction
- Image Reconstruction
- Deep Learning using TensorFlow/Keras
- Computer Vision Fundamentals

---

## 👨‍💻 Author

**Devratan**

PGDM (Business Analytics)  
Lloyd Business School

Data Scientist Intern  
Celebal Technologies

---

## 📝 Note

This repository has been created for academic submission and learning purposes as part of the **Machine Learning Foundation Program at Celebal Technologies**.
