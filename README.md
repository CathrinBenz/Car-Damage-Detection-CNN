# Car-Damage-Detection-CNN
Car Damage Detection using Convolutional Neural Networks (CNN) with image preprocessing techniques for binary classification of damaged and undamaged vehicles.

##  Overview

This project implements a Convolutional Neural Network (CNN) to automatically classify car images as **Damaged** or **Undamaged**. The system applies image preprocessing techniques to improve image quality before training the CNN model for accurate classification.

---

##  Features

- Car damage detection using Deep Learning
- Binary image classification
- Image preprocessing using OpenCV
- CNN model built with TensorFlow/Keras
- Predicts damaged and undamaged vehicles
- Image visualization of prediction results

---

##  Project Architecture

```
Car Image
     │
     ▼
Image Preprocessing
(OpenCV)
     │
     ▼
Image Resizing
(224 × 224)
     │
     ▼
Noise Reduction
(Bilateral Filter)
     │
     ▼
CNN Model
(TensorFlow/Keras)
     │
     ▼
Prediction
(Damaged / Undamaged)
```

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

##  Installation

```bash


cd CNN-Car-Damage-Detection

pip install -r requirements.txt
```

---

##  Usage

1. Load the car damage dataset.
2. Preprocess images.
3. Train the CNN model.
4. Evaluate the model.
5. Predict damage for new car images.

---

##  Project Structure

```
CNN-Car-Damage-Detection/

│── CNN CAR.ipynb
│── README.md
│── requirements.txt
│── images/
│── dataset/

```

---

##  Model Architecture

- Conv2D
- MaxPooling2D
- Conv2D
- MaxPooling2D
- Conv2D
- MaxPooling2D
- Flatten
- Dense
- Dropout
- Output Layer (Sigmoid)

---

##  Results

- Successfully classifies damaged and undamaged car images.
- Uses CNN for feature extraction.
- Image preprocessing improves model performance.

---

##  Future Improvements

- Multi-class damage detection
- Damage localization using Object Detection
- Mobile application deployment
- Real-time accident damage detection
- Transfer Learning with ResNet50/EfficientNet

