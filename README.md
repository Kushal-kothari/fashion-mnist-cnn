# Fashion-MNIST CNN Practice

This repository contains my practice project implementing and training a **Convolutional Neural Network (CNN)** on the [Fashion-MNIST dataset](https://github.com/zalandoresearch/fashion-mnist).  
The goal is to gain hands-on experience with building, training, and evaluating neural networks using **TensorFlow/Keras**.

---

## 📌 Project Overview
- Dataset: **Fashion-MNIST** (70,000 grayscale images, 10 clothing categories).
- Model: Custom **5-layer CNN** with convolution, pooling, dense, and softmax output.
- Frameworks: **TensorFlow/Keras**, **NumPy**, **Matplotlib**, **scikit-learn**.
- Accuracy Achieved: ~**90%** on test set.

---

## 🛠 Tech Stack
- Python 3.x  
- TensorFlow / Keras  
- NumPy, Matplotlib  
- scikit-learn (for metrics & confusion matrix)

---

## 🚀 Steps Implemented
1. **Seeding for Reproducibility**  
   Ensured experiments give the same results every run.  

2. **Data Preparation**  
   - Loaded Fashion-MNIST dataset  
   - Normalized pixel values to [0,1]  
   - Reshaped images to `(28, 28, 1)` for CNN input  

3. **Model Architecture**  
   - Conv2D + MaxPooling2D (x2)  
   - Flatten → Dense(64) → Dense(10)  

4. **Training**  
   - Optimizer: Adam  
   - Loss: Sparse Categorical Crossentropy  
   - Epochs: 5  

5. **Evaluation & Error Analysis**  
   - Test accuracy: ~90%  
   - Plotted training/validation accuracy & loss curves  
   - Generated **confusion matrix** and **classification report**  
   - Visualized some misclassified images  

---

## 📊 Results
- **Test Accuracy:** ~90%  
- Most confusion between **Shirt ↔ T-shirt/top** (visually similar classes)  
