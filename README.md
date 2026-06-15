
# Chest-XRay-Analysis-CNN

Deep learning-based chest X-ray pneumonia detection using a Convolutional Neural Network (CNN) with Grad-CAM visualization for explainable AI.

## Features

* Chest X-ray image classification (Pneumonia / Normal)
* Image preprocessing and normalization
* CNN-based prediction model
* Confidence score generation
* Grad-CAM heatmap visualization
* Explainable AI for medical image analysis

## Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib

## Project Workflow

1. Load trained CNN model.
2. Preprocess chest X-ray image.
3. Predict Pneumonia or Normal.
4. Generate Grad-CAM heatmap.
5. Overlay heatmap on original X-ray.
6. Display prediction and confidence score.

## Output

The model classifies chest X-ray images and highlights important regions influencing the prediction using Grad-CAM.

## Note

The dataset and trained model file (`pneumonia_model.h5`) are not included in this repository due to size limitations.
