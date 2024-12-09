# VGG16-face-detector
This repository contains a deep learning pipeline for object detection, built using the powerful VGG16 architecture. The pipeline is designed to simplify the process of training and testing object detection models by automating dataset preparation and folder structure management. The current implementation is tailored for face detection but can easily be adapted for detecting other objects.

Features
---------
Automated Dataset Preparation:
Automatically creates the required folder structure for your dataset.
Saves images captured during training and testing.

Customizable Dataset Size:
Train the model on a dataset of any size (default: 30 images).
Easily augment the dataset to improve model performance.

Transferable Design:
Although the current pipeline is optimized for face detection, it can be extended to detect any type of object by updating the training dataset and fine-tuning the model.

VGG16 Backbone:
Leverages the pre-trained VGG16 architecture for robust feature extraction.

