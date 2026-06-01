#  CNN-Based Fire Detection System

A deep learning project developed for the **Deep Learning Course Final Project**. This project uses a **Convolutional Neural Network (CNN)** to classify images as **Fire** or **Non-Fire**.

##  Project Overview

Early fire detection is crucial for preventing property damage, environmental destruction, and loss of life. In this project, a CNN model was developed and trained on a dataset containing fire and non-fire images. The model learns visual patterns such as flames, brightness, color distribution, and texture to perform image classification.

##  Objectives

* Develop a CNN-based fire detection model.
* Classify images into Fire and Non-Fire categories.
* Evaluate model performance using accuracy, loss curves, and a confusion matrix.
* Test the trained model on unseen images.

##  Dataset

Dataset used in this project:

https://www.kaggle.com/datasets/phylake1337/fire-dataset

The dataset contains two classes:

* Fire Images
* Non-Fire Images

##  Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn
* Kaggle Notebook

##  CNN Architecture

The model consists of:

* Convolutional Layers (Conv2D)
* Max Pooling Layers
* Dropout Layer
* Flatten Layer
* Dense Layers
* Sigmoid Output Layer

##  Training Results

* Validation Accuracy: **94.47%**
* Validation Loss: **0.1574**
* Epochs: **10**
* Optimizer: **Adam**
* Loss Function: **Binary Crossentropy**

##  Accuracy Curve

<img width="955" height="570" alt="Screenshot 2026-06-01 191119" src="https://github.com/user-attachments/assets/bac7a497-adba-4a75-9a21-0f5ad7c9d908" />


##  Loss Curve
<img width="933" height="582" alt="Screenshot 2026-06-01 191317" src="https://github.com/user-attachments/assets/8b2afb26-85ad-4c83-aedf-7783171a9061" />



##  Confusion Matrix

<img width="729" height="579" alt="Screenshot 2026-06-01 191426" src="https://github.com/user-attachments/assets/f149645b-4a7e-4c39-bf57-9552ebca5f43" />


##  Fire Detection Example

Example prediction on a new fire image.

<img width="594" height="432" alt="image" src="https://github.com/user-attachments/assets/5c75b699-1bb4-4a1d-b7de-d56efb4e200b" />

<img width="577" height="429" alt="image" src="https://github.com/user-attachments/assets/a1f73729-b46b-41df-a913-179e06a881d4" />



