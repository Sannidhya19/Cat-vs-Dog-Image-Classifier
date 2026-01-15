# Cat-vs-Dog-Image-Classifier
This project is a beginner-level image classification model built using Convolutional Neural Networks (CNN) and TensorFlow. The model predicts whether an image contains a **dog** or a **cat**.

---

## 📌 Project Overview

- Images are stored in CSV format
- Each image is reshaped to 100×100×3
- A CNN model is trained to classify images as Dog or Cat
- The model outputs a probability which is converted into a final class label

---

## 🛠 Technologies Used

- Python
- NumPy
- Matplotlib
- TensorFlow / Keras
- Jupyter Notebook

---

## 📂 Dataset Details

- Training images: 2000
- Testing images: 400
- Image size: 100 × 100 × 3
- Labels:
  - `0` → DOG
  - `1` → CAT

---

## 🧠 Model Architecture

- Conv2D + ReLU
- MaxPooling2D
- Conv2D + ReLU
- MaxPooling2D
- Flatten
- Dense (ReLU)
- Dense (Sigmoid)

---

## 📊 Model Performance

- Training accuracy reaches around **80%**
- Loss decreases steadily during training
- Model predicts correctly on random test images

---

## 🔍 How Prediction Works

- The model outputs a value between 0 and 1
- If value > 0.5 → CAT
- Else → DOG
- Prediction is compared with the actual label from test data

---

## 🎯 Purpose of This Project

This project was created as one of my **first CNN projects** to understand:
- Image preprocessing
- CNN layers
- Binary classification
- Model evaluation

---

## 🚀 Future Improvements

- Data augmentation
- More CNN layers
- Better accuracy
- Model deployment

---

## 👤 Author

**Sannidhya Pakrashi**  
Beginner in Machine Learning & Deep Learning
