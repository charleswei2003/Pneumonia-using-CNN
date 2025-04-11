# Pneumonia-using-CNN
<img src="chest_X-ray_for_pneumonia.png" alt="game visual" width="400"/>

## Overview
This study develops a Convolutional Neural Network (CNN) model to automate pneumonia detection using the Kaggle Chest X-Ray Dataset (https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia). The model employs two convolutional blocks for feature extraction, followed by dense layers for classification, with data augmentation techniques to address class imbalance. Trained using the Adam optimizer with binary cross-entropy
loss, the model achieved a peak test accuracy of 91%, demonstrating its potential as a reliable diagnostic aid for medical professionals.

Note: the epoch path file contains 6 key epochs. One can change the path name in the code to see how different epochs perform
