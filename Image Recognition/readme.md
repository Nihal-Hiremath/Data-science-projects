# Project Description: 🌸 Flower Image Classification using TensorFlow

This project demonstrates the development of a deep learning model to classify images of flowers using TensorFlow and Keras. The dataset used is the publicly available **"flower_photos"** dataset provided by TensorFlow, which contains several categories of flower images, such as roses, tulips, daffodils, dandelions, and sunflowers.

## Key Features

- **Dataset:** The dataset is automatically downloaded from TensorFlow's public resources and consists of labeled flower images.
- **Data Preprocessing:** Images are resized and normalized. The dataset is split into training and validation sets.
- **Data Augmentation:** Augmentation techniques like flipping and rotation are applied to improve model generalization.
- **Model Architecture:** A convolutional neural network (CNN) built using `Sequential` from Keras, with layers including `Conv2D`, `MaxPooling2D`, and `Dense`.
- **Training & Evaluation:** The model is compiled with `adam` optimizer and trained using categorical crossentropy loss. Model performance is evaluated using accuracy metrics and visualized through plots.
- **Model Export:** After training, the model can be saved for inference or further use.

This project is suitable for anyone interested in understanding the basics of image classification using CNNs and TensorFlow.

Using TensorFlow and Keras, we build a model that classifies images from the [flower_photos dataset](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz), which includes categories like roses, sunflowers, tulips, daffodils, and dandelions.

## 📂 Dataset

- Automatically downloaded using TensorFlow's utility functions.
- Contains over 3,600 labeled images across five classes.

## 🧠 Model Architecture

The model is built using the Keras `Sequential` API with the following components:
- Convolutional layers
- MaxPooling layers
- Dense layers with ReLU and softmax activation
- Data augmentation for improved generalization

## 📊 Results

- Training and validation accuracy is plotted across epochs.
- Model achieves high accuracy in flower classification with relatively simple architecture.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- PIL
