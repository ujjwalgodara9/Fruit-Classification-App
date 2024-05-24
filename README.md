# Fruit Classification App Using TensorFlow Lite

## Overview
This project involves developing a mobile application that collects a set of images and uses a Convolutional Neural Network (CNN)
to classify them into three categories: apple, orange, and banana. If the confidence level is below a certain threshold, the image 
is classified as 'other'. The implementation uses TensorFlow Lite for running the neural network on Android.

## Developer
Ujjwal Godara, IIIT Delhi Student, Mobile Computing Course 2024

## Features
- **Image Loading:** The app allows users to load images either from the camera or the gallery.
- **Image Classification:** Uses a CNN implemented with TensorFlow Lite to classify images into four categories (apple, orange, banana, other).
- **Confidence Threshold:** If the classification confidence is less than 2, the image is classified as 'other'.

## Grading Criteria
1. **Running of basic native code** – 10 marks
2. **Utilization of Native Neural Networks API** – 10 marks
3. **Activity to load images (either from camera or from a file)** – 10 marks
4. **Running of the prediction (proper running and output is important, but very high accuracy is not needed)** – 10 marks

## Installation
1. Clone the repository:
   
   git clone https://github.com/ujjwalgodara9/Fruit-Classification-App
