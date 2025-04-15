# chest_xray_classification
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

![image](https://github.com/user-attachments/assets/aaa8c287-c353-40cd-bc7a-82a13902f485)
