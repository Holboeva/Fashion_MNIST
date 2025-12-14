# Fashion MNIST Image Classification using CNN

## 📌 Project Overview
This project demonstrates an image classification task using a **Convolutional Neural Network (CNN)** trained on the **Fashion MNIST** dataset.  
The goal is to classify grayscale images of clothing items into 10 different categories.

This project was developed as part of my **Artificial Intelligence coursework** and treated as a real-world machine learning project.

---

## 🧠 Dataset
- **Fashion MNIST**
- 60,000 training images
- 10,000 test images
- Image size: 28 × 28 (grayscale)
- Number of classes: 10

Classes:
- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

---

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## 🏗️ Model Architecture
The CNN model consists of:
- Multiple **Conv2D** layers with ReLU activation
- **Batch Normalization** to stabilize training
- **MaxPooling** layers for downsampling
- **Dropout** layers to reduce overfitting
- Fully connected **Dense** layers
- **Softmax** output layer for multi-class classification

---

## 🔄 Data Preprocessing
- Normalized pixel values to the range `[0, 1]`
- Reshaped input data to match CNN input format `(28, 28, 1)`
- One-hot encoded class labels using `to_categorical`

---

## 🚀 Training Details
- Optimizer: **Adam**
- Loss function: **Categorical Crossentropy**
- Epochs: **20**
- Batch size: **128**
- Validation split: **10%**

---

## 📊 Evaluation
The trained model was evaluated on the test dataset, achieving good classification accuracy.  
Predictions were visualized by comparing **true labels** and **predicted labels** for selected test images.

---

## 📈 Visualization
- Displayed sample test images
- Compared predicted and actual class labels
- Highlighted correct and incorrect predictions

---

## 💡 Key Learnings
- Building and training CNN models for image classification
- Handling overfitting using Dropout and Batch Normalization
- Understanding the complete deep learning pipeline:
  data preprocessing → model training → evaluation → visualization

---

## 📂 Project Structure

---

## 👩‍💻 Author
**Vazira Holboeva**  
Data Science & AI Intern  
GitHub: https://github.com/Holboeva
