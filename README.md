# 🖊️ Handwritten Digit Recognition (MNIST + CNN)

## 📌 Project Overview
This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** to recognize handwritten digits (0–9) from the **MNIST dataset**.  
The model learns to classify grayscale digit images and achieves **~99% accuracy** on the test set.  

---

## 🚀 Problem Statement
Manual recognition of handwritten digits is **time-consuming** and **error-prone**, especially in large datasets like bank cheques, scanned forms, and postal codes.  
This project aims to **automate digit classification** using deep learning.

---

## 📊 Dataset
- **Source:** MNIST Dataset (70,000 images)  
- **Training set:** 60,000 images  
- **Test set:** 10,000 images  
- **Image size:** 28 × 28 pixels (grayscale)  

---

## 🏗️ Model Architecture
- **Conv2D + ReLU** → Extract spatial features  
- **MaxPooling2D** → Reduce dimensionality  
- **Flatten** → Convert 2D features to 1D  
- **Dense Layer (ReLU)** → Learn non-linear patterns  
- **Dense Layer (Softmax)** → Classify digits (0–9)  

---

## ⚙️ Training Setup
- **Optimizer:** Adam  
- **Loss Function:** Sparse Categorical Crossentropy  
- **Metrics:** Accuracy  
- **Epochs:** 10  
- **Callbacks:** EarlyStopping, ReduceLROnPlateau, ModelCheckpoint  

---

## 📈 Results
- ✅ **Training Accuracy:** ~99%  
- ✅ **Validation Accuracy:** ~98–99%  
- ✅ **Test Accuracy:** ~98.5–99%  

The model shows **high accuracy** with minimal overfitting.  

---

## 🔮 Predictions on Unseen Data
| Input Image | Predicted Digit |  
|-------------|----------------|  
| (28×28 digit image) | 7 |  
| (28×28 digit image) | 3 |  
| (28×28 digit image) | 9 |  

---

## 🛠️ How to Run
1. Clone this repo:  
   ```bash
   git clone https://github.com/<your-username>/handwritten-digit-recognizer.git
   cd handwritten-digit-recognizer
