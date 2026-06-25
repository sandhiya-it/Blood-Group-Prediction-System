Blood Group Prediction Using Blood Cell Images
📌 Overview

This project uses Deep Learning and Computer Vision techniques to predict a person's blood group from Blood cell images. A Convolutional Neural Network (CNN) is trained on Blood cell datasets to classify images into different blood group categories.

Note: This project is intended for educational and research purposes only. Blood group prediction from Blood cell is not a medically validated method and should not replace laboratory blood tests.

🚀 Features
Blood cell image preprocessing using OpenCV
Blood group classification using CNN
Automatic feature extraction from Blood cell patterns
Model training and evaluation
Blood group prediction on new Blood cell images
Visualization of training accuracy and loss

🛠️ Technologies Used
Python
TensorFlow / Keras
OpenCV
NumPy
Matplotlib
Scikit-Learn

📂 Project Structure
Blood-Group-Prediction/
│
├── dataset/
│   ├── A+
│   ├── A-
│   ├── B+
│   ├── B-
│   ├── AB+
│   ├── AB-
│   ├── O+
│   └── O-
│
├── model/
│   └── blood_group_model.h5
│
├── blood_group_prediction.py
├── requirements.txt
├── README.md
└── results/
📊 Dataset

The dataset consists of Blood Cell images categorized according to blood groups:

A+
A-
B+
B-
AB+
AB-
O+
O-

Each image is preprocessed before being used for training.
