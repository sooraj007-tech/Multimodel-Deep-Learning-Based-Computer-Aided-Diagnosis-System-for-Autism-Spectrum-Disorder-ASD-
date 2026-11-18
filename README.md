# Multimodel Deep Learning-Based Computer-Aided Diagnosis System for Autism Spectrum Disorder (ASD)

An academic deep learning project exploring image-based classification for Autism Spectrum Disorder (ASD) using Convolutional Neural Networks (CNNs) and transfer learning.

## Overview

This project demonstrates how deep learning techniques can be applied to image classification in the context of autism-related research.

It uses a CNN-based model with transfer learning to classify facial images into the categories represented in the dataset. A Flask-based application provides an interface for demonstrating the model's image prediction functionality.

**Note:** This is an educational prototype and is not a clinically validated diagnostic system.

## Objectives

- Explore deep learning techniques for image classification.
- Apply CNN and transfer learning concepts.
- Perform image preprocessing for model input.
- Develop a model-based image prediction application.
- Integrate the trained model into a Flask application.

## Technologies Used

- Python
- TensorFlow
- Keras
- Convolutional Neural Networks (CNN)
- Transfer Learning
- Flask
- Image Processing

## Project Workflow

1. **Dataset Preparation** – Prepare the image dataset for model development.
2. **Image Preprocessing** – Process images into a suitable format for model input.
3. **Model Development** – Develop a CNN-based classification model using transfer learning.
4. **Model Training** – Train the model using the prepared dataset.
5. **Application Development** – Integrate the trained model into a Flask-based web application.
6. **Prediction** – Use the application to demonstrate image-based classification.

## Important Implementation Detail: Webcam Feature

The current webcam demonstration contains a rule-based implementation.

When a face is presented to the live webcam, the application displays the result `Non_Autism`.

This is not a genuine real-time prediction made by the trained deep learning model. The webcam functionality does not currently perform actual autism classification.

This limitation should be considered when interpreting the application's output.

## Limitations

- The project is an academic prototype and has not been clinically validated.
- Model performance depends on the dataset and training process.
- Image-based classification cannot establish whether a person has Autism Spectrum Disorder.
- The webcam demonstration does not perform genuine real-time model inference.

## Future Improvements

- Implement genuine model-based real-time webcam inference.
- Evaluate the model using independent and diverse datasets.
- Improve model generalization and performance.
- Enhance the application's user interface and functionality.
- Incorporate appropriate privacy, ethical, and clinical validation requirements.

## Disclaimer

This project is developed solely for educational and academic purposes.

It is not intended to diagnose, screen for, or replace professional assessment of Autism Spectrum Disorder. No medical decisions should be made using this application.

