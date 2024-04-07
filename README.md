# Facial Recognition Deep Learning Project
# Facial Expression Recognition using Deep Learning
## Overview
This project explores the application of deep learning techniques for facial expression recognition. Two versions of the same dataset were analyzed to develop models capable of accurately identifying six facial expressions: angry, fear, happy, neutral, sad, and surprise.

## Dataset
Two versions of the dataset were used in this project, both containing images of faces labeled with their corresponding facial expressions. The sources of these datasets are as follows:

Project - Facial Recognition V1
Project - Facial Recognition V1
## Methodology
Data Preprocessing:

The images were preprocessed to enhance quality and normalize variations in lighting and facial orientation.
Data augmentation techniques such as rotation, flipping, and zooming were applied to increase the diversity of the training dataset.
Model Architecture:

Convolutional Neural Networks (CNNs) were utilized for feature extraction and classification.
Different architectures, such as VGG, ResNet, and Inception, were experimented with to find the most suitable model for the task.
## Training:

The models were trained on a portion of the dataset and validated on a separate portion to monitor for overfitting.
Transfer learning was employed using pre-trained models to leverage features learned from large-scale datasets like ImageNet.
## Evaluation:

The trained models were evaluated using metrics such as accuracy, precision, recall, and F1-score.
Confusion matrices and classification reports were generated to assess the model's performance across different facial expressions.
