Wildfire Prediction Analysis
Project Overview
This project aims to detect wildfires from satellite or aerial images using deep learning. It involves data preprocessing, augmentation, and training two models: a custom Convolutional Neural Network (CNN) and a MobileNetV2-based transfer learning model. The models classify images into Wildfire or NoWildfire categories to help early wildfire detection.

Features
Data cleaning and verification of image dataset
Image augmentation for robust training
Custom CNN model built from scratch
MobileNetV2 transfer learning for improved accuracy
Training and validation with detailed performance metrics
Visualization of accuracy and loss curves for model evaluation



Requirements
Python 3.7+

TensorFlow 2.x

Keras

Pillow

Matplotlib

Seaborn

Pandas

Install dependencies with:

bash
Copy
Edit
pip install tensorflow pillow matplotlib seaborn pandas
Usage
Place your dataset images in the respective folders (train, valid, test) with subfolders for each class (Wildfire and NoWildfire).

Run the training scripts to train both Custom CNN and MobileNetV2 models.

Visualize model performance with the provided plotting functions.

Results
The models achieved competitive accuracy in wildfire image classification.

MobileNetV2 transfer learning showed improved validation performance over the custom CNN.
