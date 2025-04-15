# Chest Xray Classification
This repository contains a complete solution for classifying chest X-ray images as either NORMAL or PNEUMONIA using a Convolutional Neural Network (CNN). This project was built following a set of specific criteria and rubric, ensuring top-notch data preparation, augmentation, and model performance.

## Overview

- **Data Preparation:**  
  The dataset is organized into three main folders: `train`, `val`, and `test`. Each folder contains subdirectories (`NORMAL` and `PNEUMONIA`) that represent the target labels for classification.

- **Data Augmentation & Normalization:**  
  The images are processed with the following steps:
  - **Resizing** to 224x224 pixels.
  - **Random Horizontal Flipping** to increase data variability.
  - **Normalization** using ImageNet's mean and standard deviation for RGB images.

- **Model Training:**  
  The project fine-tunes a pretrained ResNet18 model with:
  - **Batch size:** 4  
  - **Number of epochs:** 10  

- **Test Evaluation:**  
- The model is evaluated on unseen test data and achieves a **Test Accuracy: 0.9500**.
- This outstanding test performance confirms the effectiveness of the CNN model in differentiating between NORMAL and PNEUMONIA X-rays.

- **Classification & Visualization:**  
  After training, the CNN is used to classify unseen test images. A visualization script plots 15–20 test images with both the predicted and true labels displayed, offering a clear visual verification of the     
  model’s performance.


![image](https://github.com/user-attachments/assets/aaa8c287-c353-40cd-bc7a-82a13902f485)
