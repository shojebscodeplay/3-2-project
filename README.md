# Real-Time Border Safety Monitoring System
# Overview
This project is a comprehensive computer vision system designed for real-time monitoring of border areas. It leverages deep learning techniques for image classification and face recognition, utilizing TensorFlow and Keras for model development and OpenCV for real-time video processing. Additionally, a local host website was created to manage and display the project's results.
![Screenshot (8)](https://github.com/user-attachments/assets/34441759-24b5-4b04-9c13-eea98bfd9b77)

# Key Features
Image Classification: Utilizes a Convolutional Neural Network (CNN) model to classify images into two categories: BorderGuard and Local.
Face Recognition: Employs face recognition to identify known individuals using face_recognition library.
Real-Time Monitoring: Monitors the border area via a webcam and provides real-time alerts and actions based on the classification results.Collects data and store at thingspeak. So that this system can track both local and guards. 
Local Host Website: A local host website was developed to manage the dataset, view results, and monitor the system's performance.
How It Was Built
Data Collection:

Collected and organized a dataset of images for two categories: BorderGuard and Local.
Preprocessed the images by converting them to grayscale, resizing them, and normalizing pixel values.
Model Development:

Designed a CNN model with two convolutional layers, followed by max pooling, dropout, and dense layers.
Compiled and trained the model using the collected dataset, and saved the best model using callbacks for early stopping and model checkpointing.
Real-Time System Implementation:

Implemented a real-time video feed using OpenCV to capture frames from the webcam.
Integrated the CNN model for image classification and face recognition for identifying known individuals.
# Outputs
![Screenshot (52)](https://github.com/shojebscodeplay/Border-area-monitoring-System-using-cnn-3-2-project-/assets/70110235/7d3db3c9-1ae0-4190-bb26-ffa589513625)
