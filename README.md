# Pneumonia-Detection-Using-CNN
project Overview
The model classifies chest X-ray images into two categories: Normal and Pneumonia. It uses a publicly available dataset of labeled X-ray images, which are preprocessed by resizing to a consistent input size and normalizing pixel values for optimal model performance.
The CNN architecture extracts relevant features from images through multiple convolutional and pooling layers, followed by dense layers that output a prediction score. The model is trained using TensorFlow/Keras with techniques to prevent overfitting and improve accuracy.
To make the model accessible, a web application is built using Streamlit, allowing users to upload chest X-rays and receive real-time predictions with confidence scores.

Features
Automated pneumonia detection from chest X-rays with high accuracy
Preprocessing pipeline including resizing and normalization of images
CNN-based model built and trained using TensorFlow and Keras
Streamlit app for easy image upload and prediction visualization
Confidence score output to indicate prediction certainty

Technologies Used
Python
TensorFlow / Keras
Streamlit
NumPy, PIL for image processing

Conclusion
This project successfully uses a CNN to detect pneumonia from chest X-rays with high accuracy. The Streamlit app makes the model easy to use, helping provide quick and reliable diagnoses. This tool can support healthcare professionals and improve patient outcomes, especially where expert analysis is limited.
