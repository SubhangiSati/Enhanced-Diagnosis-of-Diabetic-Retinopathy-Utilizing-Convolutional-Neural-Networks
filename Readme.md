# Diabetic Retinopathy Detection

This project focuses on detecting Diabetic Retinopathy (DR) from retinal images using machine learning models. The goal is to classify images based on the severity of DR using deep learning techniques.

## Project Overview

Diabetic Retinopathy is a leading cause of blindness, caused by damage to the blood vessels in the retina. Early detection can prevent vision loss. This project leverages several convolutional neural network (CNN) architectures to classify retinal images into different stages of DR. The models used are ResNet50, VGG16, InsceptionV3.

## Notebooks Overview

1. **FW.ipynb**: Preprocessing steps, including resizing, normalization, and augmentation techniques for handling retinal images. It also includes initial data visualization and analysis.

2. **GB.ipynb**: Applies Gaussian blur to the retinal images as a preprocessing step to enhance model robustness against noise and image variability.

3. **M1.ipynb**: Implementation of the first CNN model for classifying diabetic retinopathy stages. Includes training, validation, and evaluation on the dataset.

4. **M2.ipynb**: Another CNN model implementation with different hyperparameters and architecture, aimed at improving accuracy and reducing overfitting.

5. **M3.ipynb**: A more advanced CNN architecture (potentially with transfer learning or custom layers) to optimize classification performance on the diabetic retinopathy dataset.

## Features

- **Image Preprocessing**: Resize, normalize, and apply Gaussian blur to retinal images.
- **Multiple Models**: Experimentation with different CNN architectures.
- **Metrics**: Accuracy, precision, recall, and F1-score to evaluate model performance.

## Dataset

The dataset used for this project contains labeled retinal images for diabetic retinopathy. The images are divided into five classes representing the severity of the disease:
1. No DR
2. Mild
3. Moderate
4. Severe
5. Proliferative DR

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/SubhangiSati/Enhanced-Diagnosis-of-Diabetic-Retinopathy-Utilizing-Convolutional-Neural-Networks
   ```
2. Install dependencies:
   ```bash
	pip install -r requirements.txt
   ```
3. Run the notebooks: Open the respective notebooks to preprocess data, train models, and evaluate their performance.
##Model Evaluation

- **Training and Validation Accuracy: Performance of models over the training and validation datasets.
- **Confusion Matrix: To analyze misclassifications.
- **Precision, Recall, and F1-Score: To assess model classification quality.
