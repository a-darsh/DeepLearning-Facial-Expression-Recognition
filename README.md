# Facial Expression Recognition using Deep Learning

This project aims at the recognition of facial expressions using deep learning techniques and data preprocessing strategies. It explores popular pre-trained models like VGG16, ResNet50, MobileNetV2, and Xception, applying transfer learning and fine-tuning to adapt them to our specific task. The project also utilizes data augmentation techniques and preprocessing strategies to try and improve the models' performance. These include face detection, alignment using OpenCV libraries, and the incorporation of Gaussian noise and batch normalization layers.

## Introduction

Facial expression recognition plays a significant role in human-computer interaction, robotics, and emotion analysis. Deep learning techniques, especially Convolutional Neural Networks (CNNs), have shown impressive results in computer vision tasks, including facial expression recognition. This project aims to create a deep learning model that can accurately recognize facial expressions from images. 

## Training the Model

The project involves training different variations of VGG16, ResNet50, MobileNetV2, and Xception models to find the best performing model for facial expression recognition. The training process includes initial training with frozen layers, fine-tuning specific layers, and incorporating additional techniques such as data augmentation, batch normalization, and Gaussian noise. Data preprocessing using face detection has also been experimented with.

## Hyperparameter Tuning

Hyperparameters such as learning rate and early stopping were adjusted, and the final hyperparameter values were chosen based on their performance on the validation set.

## Experiments and Results

Multiple experiments were conducted to assess the performance of the different model variations and fine-tuning strategies. The initial training involved training the four selected models with all layers frozen, only training the newly added fully connected layer. Subsequent experiments included fine-tuning specific layers and incorporating techniques such as data augmentation, batch normalization, and Gaussian noise. Preprocessing the data using face detection was also tested.

## Conclusion

The project offered valuable insights into the most effective techniques and configurations for Facial Expression Recognition. The results have shown significant improvement in the performance of FER systems, contributing valuable insights for future research in this domain. The project serves as a comprehensive guide for those looking to delve deeper into deep learning-based facial expression recognition.

For more details about the project and its findings, please check the project files and results folder in this repository.
