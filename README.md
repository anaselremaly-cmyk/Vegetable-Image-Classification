# 🥦 Vegetable Image Classification Using Deep Learning

## 📌 Project Overview
This project uses Deep Learning and Convolutional Neural Networks (CNN) to classify vegetable images into 15 different categories.

The model learns visual features from images and predicts the correct vegetable class.

## 📂 Dataset
The dataset contains 15 vegetable classes:
- Bean
- Bitter Gourd
- Bottle Gourd
- Brinjal
- Broccoli
- Cabbage
- Capsicum
- Carrot
- Cauliflower
- Cucumber
- Papaya
- Potato
- Pumpkin
- Radish
- Tomato

**Dataset Source:** [Vegetable Image Dataset – Kaggle](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset)

## 🧠 Model Architecture
A CNN model was built using TensorFlow and Keras.

The architecture includes:
- Input Layer: 224 × 224 × 3
- Conv2D (32 filters) + MaxPooling
- Conv2D (64 filters) + MaxPooling
- Conv2D (128 filters) + MaxPooling
- Flatten Layer
- Dense Layer
